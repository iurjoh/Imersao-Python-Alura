# Imersao-Python-Alura

[Português (Brasil)](README.pt-BR.md) | **English**

Study notes for Alura's Python immersion, "From Excel to Data Analysis". The course moves from spreadsheet exploration to Python data analysis, charts and an introduction to time-series forecasting.

**Documentation reviewed:** 2026-10-01. Course materials and notebook links below come from the original study record. External notebooks, file permissions and results were not rerun or verified in this update. This is learning material, not investment advice.

## Purpose and learning plan

| Lesson | Topics | Exercises from the original record |
| --- | --- | --- |
| 1 | B3 market data in Google Sheets; VLOOKUP, SUMIF, maximum, minimum and mean; use of ChatGPT | Weekly/monthly/annual changes, company age bands and IF formulas |
| 2 | Tables, spreadsheet charts, Google Colab and Pandas | Bar charts by age band and company count; exploring chart types |
| 3 | Data transformation with Pandas and charts with Plotly Express | Number formatting, segment pie chart and grouping by age |
| 4 | Candlestick charts, Matplotlib and interactive Plotly charts | Python tuples and an Apple stock chart with mplfinance |
| 5 | Introduction to Prophet, machine learning and data careers | The original note repeats the tuple/Apple-chart challenge; it is preserved as a course note, not a confirmed distinct assignment |

The exercises are proposals in the original record. This README does not claim they were all completed.

## Architecture and tools

```text
Market-data spreadsheet -> Google Sheets exploration
                        -> Colab notebooks -> Pandas transformations
                                           -> Plotly/Matplotlib charts
                                           -> Prophet introduction
```

This repository documents an external spreadsheet/notebook workflow, not a deployed application. Exact dependency versions and notebook execution state were not verified here.

## Course materials

- [Shared spreadsheet, lessons 1 and 2](https://docs.google.com/spreadsheets/d/1sGaR2Nkfi025rTzztCyDX7q-ZztHsK7U_SqXQr76dQ4/edit#gid=0)
- [Lesson 2 notebook](https://colab.research.google.com/drive/1Eic1tLm4vQCHpeaf_M5qNtjTTXLRPDTS?usp=sharing)
- [Lesson 3 notebook](https://colab.research.google.com/drive/1yEjLM944BiWEwBFF0-hMuLUMW-JURPya?usp=sharing)
- [Plotly bar-chart documentation](https://plotly.com/python/bar-charts/)
- [Lesson 4 notebook](https://colab.research.google.com/drive/1TrL6SbbMoZkh-8ATijWx9N8cQeTl-U4J?usp=sharing)
- [Matplotlib documentation](https://matplotlib.org/)
- [Candlestick examples folder](https://drive.google.com/drive/folders/189sYBwsNzf5KVWxcXSap_vrbSSpe5B9x)
- [Lesson 5 notebook](https://colab.research.google.com/drive/1rI0FRhchqAcna_G0To4W05bG3uxBUbFS?usp=sharing)

These are the original credited links, not freshly verified availability claims.

## Notebooks listed as the author's work

- [Lessons 1-3](https://colab.research.google.com/drive/1CI29pwrTJpODEGElsy1Zm2dX78OEppVi?authuser=0#scrollTo=SDJS4kyGAKLj)
- [Lesson 4](https://colab.research.google.com/drive/18-TZrw3cBiH4bA1ILCjdjOlZzqwf_04W?authuser=0#scrollTo=OkqDdjUd0GHQ)

The full original Portuguese lesson record is preserved in [README.pt-BR.md](README.pt-BR.md).

## Reuse, testing and snapshots

Open a linked notebook only with the access its owner permits. Use a copy and check its data sources, formulas and library versions before running it. No notebook or calculation was executed in this documentation update.

For forecasting work, check train/test separation and prediction limits. Historical stock data and model forecasts are not financial guarantees. New example charts should include dates and sources, use public data and be stored in `docs/assets/`; no new snapshot is embedded here.

## Credits and license

Alura and the course-material authors. No root `LICENSE` was found in the review. This update does not apply MIT to third-party course material or change access to any external spreadsheet or notebook.
