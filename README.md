# MVVM
MVVM is separated into 3 layers 
1- Model -> handles The data access layer whether it's web service or database (in my case data is added manually for simplicity)

2- View Model -> get the updated result from the model layer , there is no binding between the view model layer and the model layer , 
when the data is updated the changes are observed in the view layer 
3- View -> View layer only job is to recieve the action from the user and call method in View model to get the updates then display the observed updates
