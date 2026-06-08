{
  "nbformat": 4,
  "nbformat_minor": 0,
  "metadata": {
    "colab": {
      "provenance": []
    },
    "kernelspec": {
      "name": "python3",
      "display_name": "Python 3"
    },
    "language_info": {
      "name": "python"
    }
  },
  "cells": [
    {
      "cell_type": "code",
      "execution_count": null,
      "metadata": {
        "id": "o4Tm4a3S7bsy"
      },
      "outputs": [],
      "source": [
        "# E‑Commerce Sales SQL Analysis\n",
        "\n",
        "This repository contains a self‑contained SQL analysis of an e‑commerce sales dataset.\n",
        "The code runs in **Google Colab**, loads a Kaggle dataset (or creates a synthetic fallback), executes 12 important business queries, and prints the results as tables.\n",
        "\n",
        "## Features\n",
        "\n",
        "- Loads real e‑commerce data from Kaggle (`prince7489/e-commerce-sales`)\n",
        "- Automatic fallback to a synthetic dataset if the download fails\n",
        "- Renames columns to be SQL‑friendly (no spaces)\n",
        "- Creates an in‑memory SQLite database\n",
        "- Runs 12 pre‑defined SQL queries covering:\n",
        "  - Aggregations (`COUNT`, `SUM`, `AVG`)\n",
        "  - Grouping (`GROUP BY`)\n",
        "  - Sorting and limiting (`ORDER BY`, `LIMIT`)\n",
        "  - Date extraction (`strftime`)\n",
        "  - Conditional logic (`CASE WHEN`)\n",
        "  - Filtering (`WHERE`)\n",
        "- Displays each result as a clean table\n",
        "\n",
        "## Files\n",
        "\n",
        "- `sql_analysis.ipynb` – the main Colab notebook (or `.py` script)\n",
        "- `README.md` – this file\n",
        "\n",
        "## How to Run\n",
        "\n",
        "1. Open [Google Colab](https://colab.research.google.com/).\n",
        "2. Create a new notebook.\n",
        "3. Copy the entire code from `sql_analysis.ipynb` into a cell.\n",
        "4. Run the cell.\n",
        "\n",
        "No API keys or external dependencies are required (only `pandas` and `kagglehub`, which are installed automatically).\n",
        "\n",
        "## SQL Queries Performed\n",
        "\n",
        "| # | Query Description |\n",
        "|---|-------------------|\n",
        "| 1 | Total number of orders |\n",
        "| 2 | Top 5 categories by total sales |\n",
        "| 3 | Average profit per order |\n",
        "| 4 | All unique regions |\n",
        "| 5 | Region with highest total sales |\n",
        "| 6 | Monthly sales trend (first 6 months) |\n",
        "| 7 | Total profit by region |\n",
        "| 8 | Discount impact on average sales (high vs low discount) |\n",
        "| 9 | Top 5 products by sales |\n",
        "| 10 | Order count by payment mode |\n",
        "| 11 | Average sales by region |\n",
        "| 12 | Products with negative profit (top 10 losses) |\n",
        "\n",
        "## Example Output\n"
      ]
    }
  ]
}