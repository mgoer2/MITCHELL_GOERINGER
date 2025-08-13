# Custom Workout Generator

In this program, I created a widget in a jupyter notebook that allows a user to filter thousands of different exercises in order to find a specific one that works for them. In order to create this, I first needed to find a dataset that contained a lot of different exercises. While throughout the multiple sports Ive played in my lifetime I learned a lot about working out, it was nowhere near the almost 3000 exercises from this dataset. This dataset was particularly interesting because it fit my desired goals of sorting my desired body part. It is my hope that this tool can be used by many in order to help target the specific athletic goals they have in mind, while also accounting for their experience level and amount of equipment available.

# Installation

Since it is my hope that this can serve as a helpful tool to many, I attempted to make the instillation and functionality as simple as I could. This widget utilizes pandas, IPython.display, and ipywidgets. Assuming you do not have any of those or Jupyter Notebook installed, you will need to run the following commands in your anaconda prompt. 

pip install pandas

pip install ipython

pip install ipywidgets

pip install jupyter

Once you have installed all neccesary programs, you will need to download the CSV file of the Workout Dataset. I found this dataset on a website called Kaggle created by Niharika Pandit. It was originally titled "megaGymDataset.csv" but I renamed the dataset to use for this project.

https://www.kaggle.com/datasets/niharika41298/gym-exercise-data/data?select=megaGymDataset.csv

Once downloaded and renamed, you will need to place this dataset into the same folder in which you will be utilizing the widget in. Finally, open up the .ipynb file and begin generating your own custom workouts!

# How to use the Generator

As I mentioned earlier, it was my intention to make the widget as simple to use as possible since im hoping that no matter your technological knowledge, you can find this program useful. Once you have everyhing installed and downloaded (see above if not) you can begin to use the program. You will see upon running the code that there are three dropdown boxes to make choices in. The first box is where you will select the bodypart you wish to work on, simply choose one of the seventeen options, you can always change your mind later if you would like. Next you will need to select the equipment you would like to use. There are 10 broad choices when it comes to equipment so it should hopefully be able to accomadate you no matter what your available equipment is. Also, if you do not own any exercise gear or do not have a gym membership, there is a "bodyweight only" selection which can be done anywhere with simply your body. Another option is the "any" selection, this would be used by those with accsess to a commerical gym or a stocked at home gym. Finally there is a "other" option for very specific equipment that is often difficult or uncommon to find in most gyms. After you have made your first two selections, it is time to choose the level of difficulty you would like to workout at. Beginner would be recommended for anyone who is new to the fitness world or someone looking for a simpler exercise. Next is the Intermediate selection which would be used by most, those who work out semi-regularly to regularly, this is likely the best option for most people. Finally there is the Expert selection, which should be used by those who work out almost daily and are looking for a challenge, many of these exercises difficult so be warned. Once all your selections are made, click the "Display Workouts!" button and a list of workouts fitting your criteria will appear on the screen. On the output you will see the name of the exercise, the bodypart being targeted, the equipment needed, and the difficulty level. Along with these selections you'll see a sets and reps section, these are recomendations set based on your desired difficulty level and can easily be increased or decreased. You may notice that Beginner workouts contain 1 set, Intermediate 2, and Expert 3. While occasionally there may not be an exercise that fits your exact criteria, the program will increase or decrease the sets of other levels based on your desired difficulty. Lastly there is often a description of how to complete the exercise for those unfamiliar with the names.

# Notes from the Experience

Overall, I enjoyed creating this program. I have never had the opportunity to create a final project at this scale before, especially with such creative freedom and I found that reflected positively in the program. There are so many possibilities and different directions this program can be changed to reflect but I found this to be a good stopping point since it accomplished all of my desired goals. But in the future, some possible ideas to implement could include compounding different exercises together to create different plans based on amount of daily time spent working out. Another possibility could include developing a manner to track which exercises have been tried and rank them for future use. I did find many aspects interesting when creating this code and am glad with some of the features I was able to create, such as the fallback option where alternatives were provided if an exact match was not found. Another was working with widgets for the first time which was difficult at first but eventually proved to be very interesting for sorting through the dataset.
