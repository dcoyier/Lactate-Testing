# Lactate Threshold Calculator

I run cross country and track at Carleton College. I built these notebooks during a high-school project using blood lactate tests and heart-rate data to estimate aerobic (AeT) and anaerobic (AnT) threshold heart rates.

- [Preview notebook](Lactate_Threshold_Calculator_Preview.ipynb): open on GitHub to see the saved output.
- [Full notebook](Lactate_Threshold_Calculator_Full_Functionality.ipynb): run in Jupyter to adjust the lactate curve’s polynomial degree and regularization with interactive controls.

## Run the full notebook

1. Open the full notebook in Jupyter and run the dependency-installation cell.
2. Set your test stages and heart-rate time intervals. For the Garmin workflow, supply your own activity date and ID. Keep credentials in a private local copy and never commit them.
3. Enter your measured lactate values and use the interactive fit to estimate the threshold stages. Put those stage estimates into the final cell to map them to heart rate.

## Synthetic example output

With synthetic stage heart rates of 130, 140, 150, 160, 170, 180, 190, and 200 bpm (stages 1–8), the final cell’s curve fit maps these example stage estimates to:

```text
AeT stage 3.5 | HR: 155.0000
AnT stage 6.5 | HR: 185.0000
```

The example illustrates the final calculation, not a training recommendation or anyone’s test data.

[My Athletic.net profile](https://www.athletic.net/athlete/17424722/track-and-field/)
