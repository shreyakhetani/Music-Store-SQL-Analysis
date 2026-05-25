# Music Store SQL Analysis

A SQL project analyzing a digital music store database to answer business questions across Easy, Moderate, and Advanced levels.

## Database Schema

The database has 11 tables: `employee`, `customer`, `invoice`, `invoice_line`, `track`, `album`, `artist`, `genre`, `media_type`, `playlist`, and `playlist_track`.

See the full schema: [MusicDatabaseSchema.png](./MusicDatabaseSchema.png)

## Questions Answered

**Easy**
- Who is the senior-most employee?
- Which countries have the most invoices?
- Which city generates the highest revenue?
- Who is the best customer by total spending?

**Moderate**
- Which customers listen to Rock music?
- Who are the top 10 Rock artists by track count?
- Which tracks are longer than the average song length?

**Advanced**
- How much has each customer spent per artist?
- What is the most popular genre per country?
- Who is the top-spending customer in each country?

Full queries and answers: [Music_Store_Analysis_Question_And_answers.docx](./Music_Store_Analysis_Question_And_answers.docx)

## Setup

1. Clone the repo
2. Run `MusicStore_SQLServer_Setup.sql` to create the tables
3. Load the CSV files from the `/CSV` folder
4. Run the queries from the `.docx` file

## Tools Used

- SQL Server / PostgreSQL
- CSV data files

