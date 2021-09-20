# Module4_Challenge
UNCC FinTech Boot Camp Week 4 Challenge (Homework)

## Datasets used in this analysis: 

whale_navs.csv

## Libraries used in this analysis: 

pandas 
pathlib (Path)
numpy
%matplotlib 

## Answers to questions posed in starter code

1. Based on the cumulative return data and the visualization, do any of the four fund portfolios outperform the S&P 500 Index?

    Answer: None of the four fund portfolios consistently outperform the S&P 500. There are moments where the S&P 500 dips below the four funds, but never for very long. 

2. Based on the box plot visualization of just the four fund portfolios, which fund was the most volatile (with the greatest spread) and which was the least volatile (with the smallest spread)?

    Answer: Based on the box plots, the Berkshire Hathaway fund portfolio is the most volatile. The Tiger Global Management portfolio is the least volatile.

3. Based on the annualized standard deviation, which portfolios pose more risk than the S&P 500?

     Answer: None of the portfolios poses more risk than the S&P 500. 

4. Based on the rolling metrics, does the risk of each portfolio increase at the same time that the risk of the S&P 500 increases?

     Answer: The risk of each portfolio increases at more or less the same time as the S&P 500, but not as much. There are some instances where all four portfolios increase in risk at the same time as the S&P 500. There are other times where only one or two of the portfolios increases in a noticable way when the S&P 500 increases. None of the increases in risk for the four portfolios comes close to the risk of the S&P 500. 

5. Based on the rolling standard deviations of only the four fund portfolios, which portfolio poses the most risk? Does this change over time? 

     Answer: Generally speaking, the Berkshire Hathaway portfolio is the riskiest. There were times in the past when the Tiger and Soros portfolios were riskier, but in the most recents years, Berkshire Hathaway has shown itself to be riskiest. 

6.  Which of the four portfolios offers the best risk-return profile? Which offers the worst?

    Answer: The Tiger Global Management portfolio offers the best risk-return profile. The Paulson & Co. portfolio offers the worst risk-return profile. 

7. Which of the two portfolios seem more sensitive to movements in the S&P 500?
    
    Answer: The Berkshire Hathaway portfolio is more sensitive to the movements of the market. Its average beta value is 0.2215 while the average beta for Tiger Global Management's portfolio is 0.0309. Because Berkshire Hathaway's average beta value is closer to 1 than Tiger Global Managements, the Berkshire Hathaway is more likely to change in value in line withe the S&P 500 and is therefore more sensitive. 

8. Which of the two portfolios do you recommend for inclusion in your firm’s suite of fund offerings?
    
    Answer: I would be more likely to recommend the Tiger Global Management fund. It has the highest risk-return profile value and is less volatile than the Berkshire Hathaway portfolio. Overall, the best investments are long-term, safer investments, and because TGM's portfolio has a smaller standard deviation than Berkshire Hathaway, the TGM fund is less risky, making it the better choice. 
    
    
## Contributors

Giselle Taraboletti
UNCC FinTech Boot Camp

## License 

MIT License

Copyright (c) [2021] [Giselle Taraboletti]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.