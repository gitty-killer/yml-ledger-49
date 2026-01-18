# yml-ledger-49

A small Python tool that computes text statistics for ledger.

## Objective
- Provide quick text metrics for ledger documents.
- Report top word frequencies for fast inspection.

## Use cases
- Validate ledger drafts for repeated terms before review.
- Summarize ledger notes when preparing reports.

## Usage
python textstats.py data/sample.txt --top 5

## Output
- lines: total line count
- words: total word count
- chars: total character count
- top words: most frequent tokens (case-insensitive)

## Testing
- run `bash scripts/verify.sh`

## Notes
- Only ASCII letters and digits are treated as word characters.
