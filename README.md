# CSE151B_Kaggle_Competition
## Team: Azhe 
### Guideline on how to run our model:
1. The file ```./src/Kaggle_Competition_final.ipynb``` contains our final model for this Kaggle competition that helps us achieve the best score we get in the leaderboard : 597.
2. To run the file, make sure sklearn is avaliable in the tester's end, the training file ```train.csv``` is under the relative path ```../data/train.csv``` and the test file ```test_public.csv``` is under the relative path ```../test/test_public.csv```.
3. Then four models need to be run respectively: one random forest for call type C, one random forest for call type B, and two random forests for call type A. 
4. For the random forest for call type C, one more training set needs to be loaded except for ```train.csv```, which is ```train_indices.csv``` and should be within the same directory as the jupyter notebook for the codes to work properly. Then the model avaliable will be under the variable random_regressor_C. And the output are avaliable under the variable test_pred_C.
5. For the random forest for call type B, no more files are needed and the model avalibale will be under the variable random_regressor_B. And the output are avaliable under the variable test_pred_B.
6. For the random forests for call type A, no more files are needed and the model avaliable will be under the varibale random_regressor_A. Note both forests are called the same name and the output get immediately directed into the df_sample dataframe for final results. To test two models separately, it's suggested to change the name accordingly, but nothing has to be done to get the final result. 
7. Then, run though all cells provided and the result will be stored in a file ```my_pred.csv```.