# Landlord Shop Management System

A standalone, single HTML file — no installation, no server needed. Just open in any browser.

## How to Use

1. Open `LandlordManager.html` in Chrome or Edge
2. Click **Add Property** to create your properties
3. Click **+ Add Tenant** on any property card to add tenants
4. Use **Import CSV** to bulk-load tenants from a spreadsheet
5. Use **Export CSV** to download data for backup or editing in Excel

## Features

| Feature | Details |
|---|---|
| Properties | Add/edit/delete unlimited properties with location & unit count |
| Tenant Details | Name, mobile, shop no., lease start date, address |
| Financials | Monthly rent, security deposit/advance |
| Payment Status | Paid / Unpaid / Partial — toggle with one click, bulk mark paid |
| Rent Increase | Fixed amount or percentage, configurable frequency (monthly/quarterly/half-yearly/yearly) |
| Projection | View next 10 rent increases with cumulative totals |
| CSV Import | Bulk import tenants from Excel-exported CSV |
| CSV Export | Export per-property or all tenants to CSV |
| Offline | All data stored in browser localStorage — no internet needed |

## CSV Format

```
PropertyName, TenantName, Mobile, ShopNo, LeaseStart, MonthlyRent, Advance,
PaidStatus (paid/unpaid/partial), IncreaseType (none/fixed/percent),
IncreaseValue, IncreaseFreqMonths, Address
```

See `input/tenants_sample.csv` for an example.

## File Structure

```
landlord-shop-management/
├── LandlordManager.html   ← Open this in browser
├── README.md
└── input/
    └── tenants_sample.csv
```
