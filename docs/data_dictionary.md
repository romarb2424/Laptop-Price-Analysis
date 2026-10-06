# Data Dictionary

The source dataset contains 1,275 laptop records.

| Field | Meaning |
|---|---|
| Company | Laptop manufacturer |
| Product | Product/model name |
| TypeName | Laptop product type |
| Inches | Screen size |
| Ram | RAM capacity |
| OS | Operating system |
| Weight | Laptop weight |
| Price_euros | Laptop price in euros |
| Screen | Screen classification |
| ScreenW | Screen width |
| ScreenH | Screen height |
| Touchscreen | Touchscreen indicator |
| IPSPanel | IPS panel indicator |
| RetinaDisplay | Retina display indicator |
| CPU_company | CPU manufacturer |
| CPU_freq | CPU frequency |
| CPU_model | CPU model |
| PrimaryStorage | Primary storage capacity |
| SecondaryStorage | Secondary storage capacity |
| PrimaryStorageType | Primary storage technology |
| SecondaryStorageType | Secondary storage technology |
| GPU_company | GPU manufacturer |
| GPU_model | GPU model |

## Derived fields

| Field | Purpose |
|---|---|
| TotalStorage_GB | Total primary + secondary storage |
| ScreenResolution | Width x height display label |
| PriceBand | Price segment |
| WeightBand | Weight segment |
| RAM_Band | RAM segment |
| Display_Feature | Enhanced/standard display classification |
