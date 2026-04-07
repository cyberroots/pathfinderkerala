# 📋 Google Sheet Setup Guide for PathFinder Kerala

## Sheet Column Structure (22 columns)

| Column | Header | Example |
|--------|--------|---------|
| A | category | Daily Routine |
| B | question | What do you do first in the morning? |
| C | optionA | Read a book or news |
| D | optionB | Check social media |
| E | optionC | Exercise or play sport |
| F | optionD | Plan or tinker with something |
| G | wA_science | 2 |
| H | wA_commerce | 1 |
| I | wA_humanities | 0 |
| J | wA_vocational | 0 |
| K | wB_science | 0 |
| L | wB_commerce | 2 |
| M | wB_humanities | 1 |
| N | wB_vocational | 0 |
| O | wC_science | 1 |
| P | wC_commerce | 0 |
| Q | wC_humanities | 1 |
| R | wC_vocational | 2 |
| S | wD_science | 1 |
| T | wD_commerce | 1 |
| U | wD_humanities | 0 |
| V | wD_vocational | 2 |

## Weight Guide
- 0 = No relevance to this group
- 1 = Slightly relevant
- 2 = Strongly relevant

## How to Publish
1. Open Google Sheets
2. File → Share → Publish to web
3. Choose your sheet tab → CSV format
4. Click Publish and copy the URL
5. Paste URL into `SHEET_URL` variable in test.html

## Categories to Use
- Daily Routine
- Interest
- Behaviour
- Personality
