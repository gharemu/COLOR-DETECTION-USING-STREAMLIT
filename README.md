# COLOR-DETECTION-USING-STREAMLIT
This project implements a color detection model using Streamlit, identifying dominant colors in uploaded images.

*****Features******
1.Detects dominant colors in images.
2.Provides color names, hexadecimal codes, and percentages.
3.Uses K-means clustering and a pre-trained MobileNetV2 model for preprocessing.

*****Usage*****
1.Install required packages.
2.Run with streamlit run app.py.
3.Upload an image, click "Detect Color".
4.Detected colors are displayed with details.

*****Model*****
1.Image preprocessing: Resize, normalize.
2.Feature extraction: MobileNetV2.
3.Color clustering: K-means.
4.Color name resolution: Webcolors.

*****Acknowledgments*******
MobileNetV2 pre-trained model.
Webcolors for color name resolution.
