# Pan-Tompkins-algorithm-python

### About
The Pan–Tompkins algorithm is commonly used to detect QRS complexes in electrocardiographic signals (ECG). It based on paper in the [link](https://www.robots.ox.ac.uk/~gari/teaching/cdt/A3/readings/ECG/Pan+Tompkins.pdf).

### ECG QRS
![QRS](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9e/SinusRhythmLabels.svg/330px-SinusRhythmLabels.svg.png)

The Pan–Tompkins algorithm applies a series of filters to highlight the frequency content of this rapid heart depolarization and removes the background noise. The paper suggests following pre-processing steps:
![steps](https://upload.wikimedia.org/wikipedia/commons/thumb/e/eb/Pan-Tompkins_algorithm_BlockDiagram.png/1100px-Pan-Tompkins_algorithm_BlockDiagram.png)

### Results

##### Raw ECG plot
![first](images/ecg_plot.png)

##### Algorithm output plot
![last](images/final_plot.png)

### Dependencies
- numpy
- Scipy

### How to use?
- Pan_tompkins_algorithm.py is required for using the algorithm. Import it in your working. <br/>
- The class needs ECG data and its sampling rate (Hz) as inputs and it returns a signal which can be extended by finding peaks to get heart rate events. <br/>
- Check the .ipynb notebook in the repo to get started. <br/>
