# QA-for-Accessible-Charts

Building accessible data visualizations has been a topic of conversation for a while now.
There exist web-based standards as outlined in the Web Content Accessibility
Guidelines. Because of these standards, companies have had to come out with
solutions to make data visualizations accessible on the web. Most of these solutions
involve embedding data within the HTML elements that make up the figure so that a
screen reader will be able to read out the data when going through the HTML elements
of the figure. There are automatic techniques to embed data into the HTML elements of
a data visualization. At a start-up called Fizz Studio, they developed a charting package
that outputs an accessible graphic when given the data of the graph.


Unlike content on the web, there are no mandated guidelines for accessibility when it
comes to PDF formatted files, which is a big issue since the common format of research
papers is PDF. Finding a way to make PDF files accessible is very important because
research papers often use figures for reporting quantitative results and analysis. Without
methods of making the content in the figures accessible, those with visual impairments
are not able to understand the content of the figures in these papers. This is a
significant hurdle those with visual impairments have to overcome when doing work in
higher education. There are ways to make an accessible PDF file, but the process is an
extremely time-intensive one; there is no automated procedure similar to making
accessible HTML-based figures. The current process of making a PDF accessible is to
manually add tags to a PDF document by using an application like Adobe Acrobat,
which can be excessively laborious especially if you wanted to add a tag to every data
point on a scatterplot or other types of data visualizations. Simply adding a caption for a
figure does not tell the whole story of the content within a figure, so it is important to tag
all the components of a figure to provide those with visual impairments the ability to
have access to the same content as those without visual impairments (Bigham et al.
2016).


The goal of my project is to create a question answering system to query information
about a data visualization given an image of a figure. By being able to query information
from a figure, those with visual impairments will be able to access most of the same
information a visually able person can attain by
looking at the figure.

Code:
  ● MakeData.ipynb: Makes the dataset for the LSTM model. This file generates the
  questions and their associated types.
  ● Makegraphs.ipynb: makes the dataset with the chart, datatable, and associated
  question-answer pairs.
  ● ModelPredipynb: takes in the data extracted from the image and natural
  language question and outputs the response to the question.
  ● HoughOCR.ipynb: takes in the bar chart image and uses the OCR and Hough
  transform to extract data from the image.

