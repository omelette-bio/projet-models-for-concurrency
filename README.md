# projet-models-for-concurrency
This project contains the xml source file for the UPPAAL model

## How to install

Just clone the project

```
git clone https://github.com/omelette-bio/projet-models-for-concurrency.git
```

Then open UPPAAL and select the xml file

## How to execute

Now to execute, go into the "Verify" tab and select one of the two Model Checking properties to verify

## Some comments on the project

This project helped us better understand communicating automata, and formal verification through Model Checking and tools like UPPAAL.

The first property should be not satisfied, as the system is not fooled about who the initiator is.
The second one should be satisfied, as the delay are good enough to let everyone communicate properly.

To test other configurations, you can try to modify the constant values, due to a lack of time we couldn't push the tests very far.