# Portfolio Optimization Application User Guide
  
  <br>
This program helps a user optimize investment asset allocation by maximizing expected return for a particular level of risk. The application is most helpful to users with a basic knowledge of principles of asset allocation/ diversification covered in Modern Portfolio Theory.  

<br>  

**How to Use the Application**

At the bottom of the screen, there are 11 inputs: 10 return expectation inputs for each of the 10-asset class investment portfolio and one "minimum weight" constraint input. Each return input reflects the user's forward-looking annualized performance expectation for a particular class.  For example, if the user expects emerging market equity will average a 12% annual return, move the associated slider input for emerging market equity to 12.

The application also includes a minimum weight constraint. When an optimization is unconstrained (i.e., minimum weight = 0%), the resulting portfolio is typically concentrated in a single or small number of classes/investments. An investor may want to have some level of exposure to all asset classes - the minimum weight constraint is built for this purpose.

After inputting all 10 return expectation and (optionally) the minimum weight constraint input, the user is ready to click the Submit button.  
<br>
**Interpreting Results**

The application generates two charts: (1) an Efficient Frontier, and (2) an Asset Transition Map. 

*Efficient Frontier*

The Efficient Frontier is charted using a set of "optimal" portfolios that produce the highest level of expected return per unit of risk (or alternatively, the lowest level of risk per level of expected return). Risk increases along the horizontal axis, and expected return increases up the vertical axis. Note that when a portfolio is constrained (minimum weight > 0%), at least one asset class will lie outside (i.e., above) the efficient frontier.

*Transition Map*

As risk changes, so does the composition of the optimal portfolio. The Transition Map is a color chart depicting the %weights for each asset class. Conservative portfolios lie to the left of the graph, becoming increasingly aggressive when moving right on the horizontal (risk) axis.

**Known Issue** -  For some versions of Internet Explorer, the arrows on the minimum weight constraint input do not display: as a workaround, the user should manually input the constraint (e.g., 0, 1, 2, 3, 4 or 5). 
