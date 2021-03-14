# Portfolio_Optimization_Efficient_Frontier

Portfolio optimization is the core for any Asset Management Company.

Inputs to the program :

1.) Symbols List : choose any company from yahoo finance and input their symbol in a list.

2.) Start Date   : Input start date in strings in this format, 'yyyy-mm-dd'. For example : '2011-12-31' 

3.) End Date     : The default input will be the current day's date. You can choose any date you wante. (end date > start date)

4.) N_iter       : Number of iterations to perform. If N_iter = 1000, then the program will calculate the risk and return of the portfolio 1000 times.

5.) target_return_arr : an array of all the target return on which you want to optimize. You can use numpy arange to choose an array between two poits.

After the input is fed, it calculated the drawa the EFFICIENT FRONTIER.
