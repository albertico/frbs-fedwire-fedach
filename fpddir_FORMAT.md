# Fedwire Directory File Format

**Source:** https://frbservices.org/EPaymentsDirectory/fedwireFormat.html

| Field Name | Length | Columns |
| --- | --- | --- |
| Routing Number | 9 | 1-9 |
| Telegraphic Name | 18 | 10-27 |
| Customer Name | 36 | 28-63 |
| [State or territory abbreviation](https://frbservices.org/EPaymentsDirectory/states.html) | 2 | 64-65 |
| [City](https://frbservices.org/EPaymentsDirectory/fedwireCities.html) | 25 | 66-90 |
| Funds transfer status: <br/> Y - Eligible <br/> N - Ineligible | 1 | 91 |
| Funds settlement-only status: <br/> S - Settlement-Only | 1 | 92 |
| Book-Entry Securities transfer status: <br/> Y - Eligible <br/> N - Ineligible | 1 | 93 |
| Date of last revision: YYYYMMDD, or blank | 8 | 94-101 |
