# HistomorphometryMeasurer
A measurement tool for Histomorphometry. This tool could help measure lines in histomorphometry, automatically record measurements and output, for a whole batch of many images to be processed. The images are presented in a deterministic shuffled order, and real file names are hidden from users to eliminate bias in reading.

As a requirement, you will need JRE installed. And then use the following command line to start the application (linux/macOS, Windows not tested):

```sh
java -jar ./out/artifacts/ViewerApp_jar/ViewerApp.jar
```

## User Guide
1. Select Folder

File -> Open Folder

2. Set Adjustment

2.1 Mark the line of known length (use mouse to drag a line)

2.2 Set the length number into text box under "Number"

2.3 Set the actual unit into text box under "Unit"

2.4 Click "Set Adjust"

3. Measure

3.1 Mark the line to be measured (use mouse to drag a line)

3.2 Click "Measure" button

4. Next/Prev

4.1 Click "Next" button, and repeat from 2.1 (if new legend is needed) or 2.2 (if the ledend is the same)

4.2 (optional) Click "Prev" button to go back to previous image

5. Output

Click "Output" button to write the output into the `output.csv` file in project folder



## Versions
### Version 0.1 (v0.1)
This is the very first version of the application. It created a runnable (and workable) Java application, in order to help with measurements in histomorphometry. In this version, only measurements of lines are supported; curves or paths are not supported. Only one (the last one) measurement for each sample picture will be recorded. Only ".jpeg" files are supported. Images are defaulted to be zoomed 200%.

TODO:

- [ ] Support for other image formats
- [ ] Output file name without extension (??)
- [ ] Set zoom scale by user
- [ ] Custom output folder
- [ ] Multiple measurement
- [ ] Curve measurement


## Feedback
All feedbacks are welcome. Current source codes are not public, but it is arranged to be public in the future.
