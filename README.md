name: Example
uses: lowlighter/metrics@latest
with:
  template: terminal
  filename: metrics.terminal.svg
  token: ${{ secrets.METRICS_TOKEN }}
  base: header, metadata
