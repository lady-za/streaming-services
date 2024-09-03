# Overview
Since the COVID-19 pandemic, with most of the national population staying at home, there has been a decline in number or ways we used to keep ourselves entertained and a rise in number of streaming service such as Netflix,Disney,Hulu and Amazon. People want the comform to watch what they want and when they want,and parents also gain a control in what thier little ones are watching. Traditional cable and satellite service also hopped into this new change as they are now able to offer these services on thier platforms. Prediction of the future with 5G and virtual reality, this will make the viewing experince like never before.
# Problem Statement
The issues that was raised by the film academy and national regulator was that the dataset for these streaming services are stored as raw file with some fields that need to be processed, the data contains thousands of rows and they would want overview of a dashboard with key indicators, and some machine learning visuals can be build to do some prediction based on these historical data.
# Orchestration Solution
![My Image](https://github.com/lady-za/streaming-services/blob/59ec1b0500cdb7fda78d79753d2cdb943d741b55/Diagrams/Projects-Streaming%20Services.jpg)

1.Data Source

2.Orcherstration
  - Ingestion
  - Data Store
  - Tranform
  - Data warehouse:Stategies[Merge and Join on dimension and fact]
  - Applying non-clustered index on non-primary/bk coloumns

3.Visualization
- RLSImplementation(query folding, external tools)
- CLSImplementation(coloumn level security)

4.Data Activator/Incoming Webhook
