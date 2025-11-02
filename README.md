# zaproskimark

## ZA - Pro Skincare Market

This repository contains structured data for the South African Pro Skincare Market analysis.

### Market Structure

The market data is organized into three main categories:

#### 1. By Type
- **Face Care**
  - Cleansers & Exfoliators
  - Face Masks
  - Face Moisturizers
  - Other Face Care Products
- **Body Care**
  - Body Lotions/Moisturizers
  - Body Wash and Shower Gel
  - Other Body Care Products

#### 2. By Packaging Type
- Tube
- Bottles
- Jars

#### 3. By Distribution Channel
- Offline Retail Stores
- Online Retail Stores
- Specialist Retail
- Super-/Hyper-markets
- Convenience/Grocery
- Pharmacies/Drug
- Online Retail Channels
- Other

### Documentation

- **Detailed Analysis**: See [south_africa_skincare.md](south_africa_skincare.md) for comprehensive market segmentation details
- **Data Format**: The market structure is available in JSON format in `za-pro-skincare-market.json`

### Usage

```bash
# View the market structure
cat za-pro-skincare-market.json

# Pretty print the JSON
python3 -m json.tool za-pro-skincare-market.json

# Read detailed market analysis
cat south_africa_skincare.md
```