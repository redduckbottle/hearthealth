
# Heart Health Insights Using MIT-BIH ECG Data

This project performs basic ECG signal analysis using the MIT-BIH Arrhythmia Database.  
It focuses on extracting key cardiac features such as R-peaks, heart rate, and RR-interval variability.

The goal is to create a beginner-friendly but complete biomedical signal analysis workflow suitable for academic learning, internships, and introductory research projects.


## Features

- Load ECG data from the MIT-BIH Arrhythmia Database
- Plot raw ECG waveform
- Detect R-peaks using signal processing
- Calculate:
  - Total beats
  - Average heart rate (bpm)
  - Bradycardia / Tachycardia classification
- Save results as:
  - PNG plots
- Well-documented Google Colab notebook for easy execution




## How to Run the Project

1. Open the `notebooks/ecg_analysis.ipynb` file in Google Colab.
2. Download the MIT-BIH Arrhythmia Database from:
   https://physionet.org/content/mitdb/1.0.0/
3. Upload the extracted folder to your Colab session.
4. Update the path in the notebook if needed.
5. Run the notebook cells to generate:
   - ECG plots
   - R-peak detection visualization
   - Heart rate and RR-interval statistics
     

## Requirements

Install the required Python packages:

pip install wfdb scipy matplotlib numpy pandas


## Outputs

All generated outputs are stored in the `results/` folder:

- `ecg_plot.png`
- `r_peaks_plot.png`
- `ecg_analysis_results.csv`

These files are produced automatically when the notebook runs.


## Future Enhancements

- Add Butterworth filtering for noise removal
- Classify arrhythmias using MIT-BIH annotations
- Build a simple GUI to upload ECG images
- Compare multiple ECG records automatically


## License

This project uses publicly available data from PhysioNet under their open-data license.


