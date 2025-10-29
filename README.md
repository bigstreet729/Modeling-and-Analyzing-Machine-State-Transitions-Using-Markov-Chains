A very simple project on first order markov chain modelling .
1) Imagine you are given a sequence of states of a system now you want to analyze this systems behaviour.
2) Estimations: You count all transtions from current state to particulat possible states in the sequence and divide by count of current state to get the transition probability of curr state to particular possible states.
3) This estiamtion is a first order markov modelling assumpotion , if you assume next state depends on previous two states you need to estiamte accordingly.
4) At the end you solve the steady state probabilities by solving pi*T=pi.
5) If you observe the graph you find some insights in the transitions.Where Fully operational state is not frequent enough this is a very unstable which is not desired in actual systems in real world. To mitigate this you need to look out for factors which causes this then your transtion proabability
