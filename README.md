# Sign Language Detection with Action Recognition and LSTM Deep Neural Network

This is a Sign Language Detection Project 📽. What it does is detect hand-signs in realtime using OpenCV and TensorFlow LSTM Model. The current model is trained on detect "I Love You ♥", "Hello 👋", "Thank You🎇", "Volume Up 🔊" and "Volume Down 🔈" hand signs.

Though, this can be modified to detect any handsigns and even body poses. 

# ❓ How to add more hand-signs/actions ❓

In order to add more actions, you just need to modify this line in the code under `Setup Folder for Data Collection`.

```Python
actions = np.array(['hello', 'thanks', 'iloveyou','volup','voldown'])
```

You can add here any number of signs you want to detect, and the code will automatically create all the necessary folders to get the data during the `Data Gathering process` and train the model accordingly. 

# ❓ How to run the notebook ❓
Well, that will be easy peasy. You just need to create a conda environment using:

```Bash
conda create -n new_env_name
```

Do not forget to activate the new environment:

```Bash
conda activate new_env_name
```

And install all the dependencies to run the notebook:

```Bash
pip install -r requirements.txt
```

⚠ I am running `Python 3.6` in this project, so if you run into any issues running the notebook, switch 🔄 the python version to 3.6. I have checked, everything runs with this python version.

⚠ If you are using TensorFlow with CPU, it might take some time to train the model, so if you are in a hurry, change the number of epochs or have some damn patience. Using a GPU should be fairly quick to train the model.

⚠ Please 🙏 make sure to capture all the training data in fairly good lighting conditions to capture good and clean training data so that the model can be as accurate as possible to recognise all the hand-signs that you train for. 

# References

This was based on a YouTube Tutorial by Nicholas Renotte 👍 🏁.  