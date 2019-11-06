# COLAB
----------
1.Using numpy and pandas for array operations, data structure and analytics operations.

2.Using json for accessing the data in notebook.

3.Using pytesseract as OCR tool.

4.Using Pillow for Reading, Cropping, Manipulating the Images.

5.The data is split into 3 Dataframes as 'content', 'annotation' and 'extras'.

6.The 'extras' is neglected for not containing any useful data.

7.the 'content' has image URL of dataset which is loaded with response library.

8.The Dataframe 'content' has a set of data in itself, so converting content as Dataframe again to access the data in it.

9.The 'content' Dataframe contains 'label', 'notes', 'points', 'imageWidth' and 'imageHeight'.

10.The label contains a string "numberplate" which is neglected and the notes is null so it is also neglected.

11.The remaining data is separated as 'imageWidth', 'imageHeight' and 'points'.

12.The points contained a data table so it is again converted to Dataframe.

13.The 'points' Dataframe has 'x' and 'y' co-ordinates of the numberPlate.

14.All these data are fed to PIL and tesseract OCR for processing and a string with variable text is made to be output.
