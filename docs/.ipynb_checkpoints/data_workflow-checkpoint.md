# Workflow for Intermountain analysis:
- Create SQL and load to a final table in sandbox in interactive IDE (SQL Developer best at the moment)
- R or Python script to pull the final table (or have the full SQL section run including the write to .csv or similar)
    - Possible to do this within the SQL script and cache?
- Munge file in R or Python
- Write processed dataset to .csv or .Rdata? (What preserves labels?)
- Write out each analysis into a separate notebook