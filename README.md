# Make grid of Images by passing in list of file paths to those images



# Some visualization for doing dual y-axis and how to make multiple subplots of all columns in a dataframe with for-loop

The work was done by this person and I am loading it here for my own personal use.
https://www.kaggle.com/artgor/seismic-data-eda-and-baseline

# To more color channels in numpy just to array.transpose(index_of_axis_here, index_of_axis_here, index_of_axis_here)
For example is img is an array and shape (224, 210, 3) and you need to move the axis you can just do img.transpose(2, 0, 1) which
will turn it into (3, 224, 210).
