### README for SQLi Exfiltration Script

## Usage
Run the script with the following syntax:
```bash
python exploitBbased.py <url> <sql_query>
```

### Example
To extract the current database name from a vulnerable target:
```bash
python exploitBbased.py "http://example.com/reset_password" "SELECT database()"
```