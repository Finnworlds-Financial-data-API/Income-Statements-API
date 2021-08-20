
<h1>Income Statements API - Finnworlds</h1>

<p><a href="https://finnworlds.com/finance-data/income-statements-api/">The Income Statements API</a> is available through JSON REST API and our databases are also downloadable as an excel or csv file.  We have historical income statements in our database from the IPO of all publicly traded companies. Through our API you can request individual components of the income statement over the history of a company, or you can request the entire income statement based on ticker symbol or ISIN number of a company. The API is very intuitive and easy to use</p>



<p><a href="https://finnworlds.com/">Finnworlds</a> Our clients are big enterprises as well as individual developers who use the financial data to develop their platforms without having to worry about maintaining an actual database. We take this worry away so that you can focus on your core business.</p>




<p><a href="https://finnworlds.com/pricing">Sign up for an API key</a> to get started with the data right away. We don't have free packages on the website but for students we can do something. Just email us and lets talk about it.</p>



<h2>API Features</h2>



<ul><li><strong>Historical income statements</strong></li><li><strong>Current income statements</strong></li><li><strong>Filter by individual components</strong></li><li><strong>Extract income statements from multiple companies at once</strong></li></ul>


<h2>How to access the data</h2>



<ul><li><strong>JSON rest API</strong></li><li><strong>Excel CSV download</strong></li><li><strong>PDF reports</strong></li><li><strong>Email link</strong></li></ul>



<h2>Documentation</h2>



Our <a href="https://finnworlds.com/documentation">documentation</a> includes input parameters, output objects with explanation of their meaning, we also provide clear examples on the documentation page of various endpoints and their output. On top of this we have SDKs for Javascript, JQuery, VueJS, Angular, JAVA, PHP, NodeJS, Python, Go, Ruby, C#, R, Strest, Rust, Swift and Scala</p>


<h2>Examples</h2>

<p>https://finnworlds.com/api/v1/incomestatements?key=YOUR-KEY&stock_ticker_symbol=aapl</p>



    "status": {
        "message": "Success"
    },
    "results": [
        {
        "basics": {
            "name": "Apple Inc",
            "stock_ticker_symbol": "AAPL"
            "isin_identifier": "US0378331005"
            "exchange": "nasdaq"
            "industry": "technology"
            "sector": "consumer electronics"
        },
        "output": {
            "total_revenue": "347,155,000",
            "operating_revenue": "347,155,000"
            "cost_of_revenue": "204,804,000"
            "gross_profit": "142,351,000"
            "operating_expense": "42,413,000"
            "operating_income": "99,938,000"
            "net_non_operating_interest_income_expense": "345,000"
            "other_income_expense": "577,000"
            "pretax_income": "100,860,000"
            "tax_provision": "14,058,000"
            "net_income_common_stockholders": "86,802,000"
            "diluted_ni_available_to_com_stockholders": "86,802,000",
            "basic_eps": ""
            "diluted_eps": ""
            "basic_average_shares": ""
            "diluted_average_shares": ""
            "total_operating_income_as_reported": "99,938,000"
            "total_expenses": "247,217,000"
            "net_income_from_continuing_and_discontinued_operation": "86,802,000"
            "normalized_income": "86,802,000"
            "interest_income": "2,952,000"
            "interest_expense": "2,607,000"
            "net_interest_income": "345,000"
            "ebit": "103,467,000"
            "ebitda": "114,464,000"
            "reconciled_cost_of_revenue": "204,804,000"
            "reconciled_depreciation": "10,997,000",
            "net_income_from_continuing_operation_net_minority_interest": "86,802,000"
            "total_unusual_items_excluding_goodwill": "0"
            "total_unusual_items": "0"
            "normalized_ebitda": "114,464,000"
            "tax_rate_for_calcs": "0"
            "tax_effect_of_unusual_items": "0"
        }
    [





<p>https://finnworlds.com/api/v1/incomestatements?key=YOUR-KEY&sector=technology&industry=consumer_electronics&income_statement=total_revenue&year=2021</p>



    "status": {
        "message": "Success"
    },
    "results": [
        {
        "basics": {
            "name": "Apple Inc",
            "stock_ticker_symbol": "AAPL"
            "isin_identifier": "US0378331005"
            "exchange": "nasdaq"
            "industry": "technology"
            "sector": "consumer electronics"
            },
        "output": {
            "total_revenue": "347,155,000",
            },
        "basics": {
            "name": "Microsoft Corporation",
            "stock_ticker_symbol": "MSFT"
            "isin_identifier": "US5949181045"
            "exchange": "nasdaq"
            "industry": "technology"
            "sector": "consumer electronics"
            },
        "output": {
            "total_revenue": "168,088,000",
            },
        "basics": {
            "name": "Dell Technologies Inc",
            "stock_ticker_symbol": "DELL"
            "isin_identifier": "US24703L2025"
            "exchange": "NYSE"
            "industry": "technology"
            "sector": "consumer electronics"
            },
        "output": {
            "total_revenue": "96,814,000",
            },
        "basics": {
            "name": "...",
            "stock_ticker_symbol": "..."
            "isin_identifier": "..."
            "exchange": "..."
            "industry": "technology"
            "sector": "consumer electronics"
            },
        "output": {
            "total_revenue": "...",
            }
        "basics": {
            "name": "...",
            "stock_ticker_symbol": "..."
            "isin_identifier": "..."
            "exchange": "..."
            "industry": "technology"
            "sector": "consumer electronics"
            },
        "output": {
            "total_revenue": "...",
            },
        }
    [




<h2>Customer Support</h2>

<p>Need help, have questions? <a href="mailto:support@finnworlds.com">Get in touch with Support</a>.</p>

<h2>Legal</h2>

<p>Use of the Finnworlds website, services like API and database are subject to the&nbsp;<a href="https://finnworlds.com/legal/terms-and-conditions-on-finnworlds-data/">Finnworlds terms &amp; Conditions</a></p>
