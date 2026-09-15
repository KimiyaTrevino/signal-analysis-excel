# Signal Analysis and FFT in Excel

A medical imaging course project exploring signals in the time and frequency domains using Microsoft Excel.

## Signals
- g1(t) = 2 sin(2πt): 1 Hz
- g2(t) = 3 sin(6πt): 3 Hz
- g3(t) = 0.7 cos(12πt): 6 Hz

I used 64 samples with a time interval of 0.05 seconds.

## Method
1. Generated and plotted the three signals together.
2. Created g4 = g1 + g2 and g_total = g1 + g2 + g3.
3. Applied Excel's Fourier Analysis tool to both combined signals.
4. Used IMABS to calculate the FFT magnitudes and plotted all 64 frequency bins.

## Results
The FFT of g4 shows the 1 Hz and 3 Hz components. Adding g3 introduces a 6 Hz component in the FFT of g_total.

The full FFT magnitude has mirrored peaks because the input signals are real-valued. Peaks spread into nearby bins because the signal frequencies do not align exactly with the FFT bins.

## Plot details
- Horizontal FFT axis: frequency index k (0–63)
- Frequency spacing: 0.3125 Hz per bin
- Vertical FFT axis: unnormalized FFT magnitude

## Tools
Microsoft Excel, Analysis ToolPak, and spreadsheet formulas.

## Workbook
Open Signal_Analysis_FFT.xlsx in Excel to view the data, calculations, and four plots.
