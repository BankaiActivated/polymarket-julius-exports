# polymarket-julius-exports

Polymarket bot CSV exports for Julius.ai analysis.

## Files

| File | Description |
|------|-------------|
| `trades_enriched.csv` | Enriched closed trades with PnL, exit reasons, holding time, and market metadata |
| `decisions_export.csv` | Full bot decision log (entries, holds, exits) with signals and context |

## Import into Julius.ai

1. Go to [Julius.ai](https://julius.ai) and open a new chat or notebook.
2. Click **Add data** / **Upload** and choose **Import from URL** (or download the CSVs below and upload manually).
3. Paste one of the raw GitHub URLs:

   **Trades (enriched):**
   ```
   https://raw.githubusercontent.com/BankaiActivated/polymarket-julius-exports/main/trades_enriched.csv
   ```

   **Decisions (full log):**
   ```
   https://raw.githubusercontent.com/BankaiActivated/polymarket-julius-exports/main/decisions_export.csv
   ```

4. Example prompts for Julius:
   - *"Summarize win rate and average PnL by exit_reason_category from trades_enriched.csv"*
   - *"Plot decision_type frequency over time from decisions_export.csv"*
   - *"Which slugs had the best pnl_pct in trades_enriched.csv?"*

## Raw URLs

- **trades_enriched.csv:** https://raw.githubusercontent.com/BankaiActivated/polymarket-julius-exports/main/trades_enriched.csv
- **decisions_export.csv:** https://raw.githubusercontent.com/BankaiActivated/polymarket-julius-exports/main/decisions_export.csv
