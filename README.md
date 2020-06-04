# Word_Generation

A word generation tool using Markov Chains, built with Python
Credit to [Gustavo Zomer](https://towardsdatascience.com/generating-startup-names-with-markov-chains-2a33030a4ac0)


--------------------------------------------------------------------------------------------


### Example usage:

_import **mc_gen**_ 
_chain = mc_gen.**build_markov_chain**(mc_gen.**load_words**("words_alpha"),4)_
_mc_gen.**generate**(chain)_

Use higher values in the **build_markov_chain** function for more realistic results.