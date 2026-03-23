# NRD Lists

Daily newly registered domain (NRD) feeds, updated automatically.

Aggregated from ICANN CZDS zone files, Certificate Transparency logs, and community NRD sources. Deduplicated and sorted.

## Feeds

| File | Description | Update Frequency |
|------|-------------|-----------------|
| `nrd-today.txt` | Domains registered today (all sources) | Daily |
| `nrd-week.txt` | Domains from the last 7 days | Daily |
| `czds-nrd.txt` | CZDS zone file new domains (last 24h) | Daily |
| `ct-domains.txt` | CT log discoveries (last 24h) | Daily |
| `nrd-full.txt` | Complete master list (all domains in DB) | Daily |

## Usage

Raw URLs for direct consumption:

```
https://raw.githubusercontent.com/cryphorix/nrd-lists/main/nrd-today.txt
https://raw.githubusercontent.com/cryphorix/nrd-lists/main/nrd-week.txt
https://raw.githubusercontent.com/cryphorix/nrd-lists/main/czds-nrd.txt
https://raw.githubusercontent.com/cryphorix/nrd-lists/main/ct-domains.txt
https://raw.githubusercontent.com/cryphorix/nrd-lists/main/nrd-full.txt
```

## Format

Plain text, one domain per line. Lines starting with `#` are comments containing metadata (date, count, source).

## License

This data is provided as-is for security research and threat intelligence purposes.
