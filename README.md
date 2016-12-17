# dl4j-rnn-timeseries-examples
This is an example of DL4J's Recurrent Neural Networks applied to timeseries data

## Working with the PhysioNet Example

* git clone the repo
* update the schema as needed - https://github.com/jpatanooga/dl4j-rnn-timeseries-examples/blob/master/src/test/resources/physionet_schema.txt
* the system will automatically download PhysioNet data when it runs
* the outcomes / labels are already included in the repo
* tune the model by changing hyperparameters and running: https://github.com/jpatanooga/dl4j-rnn-timeseries-examples/blob/master/src/main/java/org/deeplearning4j/examples/rnn/strata/physionet/PhysioNet_LSTM_Model.java

## ToDo

* the current state of the PhysioNet LSTM seems to train (avg loss drops, but hyperparameter tuning appreciated)
* we dont yet have the evaluation code complete as of sunday night (main todo as of right now)

## PhysioNet Stuff

* http://physionet.org/challenge/2012/


