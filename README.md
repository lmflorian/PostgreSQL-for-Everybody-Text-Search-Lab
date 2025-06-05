# PostgreSQL Text Search Lab

This repository contains my work for the "PostgreSQL for Everybody" course (Coursera) text search lab. It demonstrates PostgreSQL's full-text search capabilities using different data sources.

## Lab Objectives

- Implement PostgreSQL full-text search on structured and unstructured data
- Compare different text search indexing methods (GIN, GiST)
- Analyze performance of text search queries
- Work with real-world data including books and email corpora

## Key Features

1. **Basic Text Search**: Simple Python-PostgreSQL connection and data insertion
2. **Book Search**: Indexing and searching Project Gutenberg text content
3. **Email Search**: Processing and searching email message bodies
4. **Advanced Search**: 
   - Phrase search
   - Boolean operators
   - Ranking algorithms
   - Language-specific indexing

## Setup Instructions

1. Clone this repository
2. Install dependencies:
   ```bash
   pip install psycopg2
