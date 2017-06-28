Multiple modes, triggered by "new-line"-ish characters:
  * Numerical
    * does "traditional" calculations
    * prints each calculation result to the stack
  * Symbolical
    * solves equations leaving variables as variables
    * prepares statements for:
  * Graphing
    * This displays a graph of given data
  * String
    * text manipulation
    
New-line-ish characters:
  * Numerical
  * Numerical w/ stack collapse
  * Symbolical
  * Graphing
  * String
  * String w/ stack collapse

Functions:
  * Unary operators are postfix notation (√, -(neg))
  * Binary operators are infix notation (+, *)
  * Tridary?+ operators are infix, one+ divider may be a NL-ish char, though. i.e.
    * <pre><code>Arg1-*NL*
      Arg2-*Func*-Arg3</code></pre> 
    * Alternately, the operator may pull all inputs from the stack
  
