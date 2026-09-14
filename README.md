VaR Monte-Carlo simulation of a trading book of vanilla European options. 
Calibrates quadratic local vol parameters from a volatility surface, simulates underlying spot paths and finds P&L distributions & VaR. 
Repeats the process but introduces delta hedging and finds new P&L distributions and reduced VaR.

Source code censored for university academic integrity purposes but can be provided upon request.

Graphical results are found below:

Call surface for 'Orinoco':

<img width="648" height="658" alt="Unknown-4" src="https://github.com/user-attachments/assets/9fef4570-da1a-4d2a-84a9-3c591ab3bd91" />

Put surface for 'Orinoco':

<img width="648" height="658" alt="Unknown-3" src="https://github.com/user-attachments/assets/661a7570-5484-4ae2-af3c-82f36df2600b" />

Complete option surface:

<img width="648" height="658" alt="Unknown-5" src="https://github.com/user-attachments/assets/c247eb03-110e-475d-861d-ba7d2286662e" />

Quadratic local vol model:

<img width="645" height="658" alt="Unknown-6" src="https://github.com/user-attachments/assets/56235ab9-8471-47cd-b05e-9649da3ec7cd" />

Monte Carlo results based on quadratic local vol model:

<img width="850" height="547" alt="Unknown-7" src="https://github.com/user-attachments/assets/f3865872-4ed9-4a97-b601-453d5cf31b8c" />

Price distribution, Local vol MC vs BSM MC:

<img width="850" height="547" alt="Unknown-7" src="https://github.com/user-attachments/assets/9d9c7e5a-ec39-4edd-ad89-f3a37635416d" />

P&L distribution of unhedged book:

<img width="571" height="455" alt="Unknown-8" src="https://github.com/user-attachments/assets/18019b25-55e1-47a0-97dd-91e0b038bee5" />

P&L distribution of delta-hedged book:

<img width="571" height="455" alt="Unknown-9" src="https://github.com/user-attachments/assets/c43c6a2b-d952-40b0-9786-376418a02d00" />



