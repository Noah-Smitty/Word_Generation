# Word_Generation

A word generation tool using Markov Chains, built with Python
Feel free to use in your own projects

###Example usage:

_import **mc_gen**_ 
_chain = mc_gen.**build_markov_chain**(mc_gen.**load_words**("words_alpha"),4)_
_mc_gen.**generate**(chain)_

Use higher values in the **build_markov_chain** function for more realistic results.