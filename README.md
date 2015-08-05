## finance.vim

Simple plugin for checking your stock in Vim (Yahoo Finance).

![Screenshot](snapshot.png)


## Requirements

- [webapi-vim][]

## Usage

    :Finance
    :Finance 0005.HK
    :Finance 0005.HK GOOG

## Install

*  [Pathogen](https://github.com/tpope/vim-pathogen)
  * `git clone https://github.com/7kfpun/finance.vim.git ~/.vim/bundle/finance.vim`
*  [vim-plug](https://github.com/junegunn/vim-plug)
  * `Plug '7kfpun/finance.vim'`
*  [NeoBundle](https://github.com/Shougo/neobundle.vim)
  * `NeoBundle '7kfpun/finance.vim'`
*  [Vundle](https://github.com/gmarik/vundle)
  * `Plugin '7kfpun/finance.vim'`

## Settings

    let g:finance_watchlist = ['0005.HK', 'GOOG']
    let g:finance_format = '{symbol}: {LastTradePriceOnly} ({Change})'
    let g:finance_separator = "\n"

## QuoteProperty

    AfterHoursChangeRealtime
    AnnualizedGain
    Ask
    AskRealtime
    AverageDailyVolume
    Bid
    BidRealtime
    BookValue
    Change
    ChangeFromFiftydayMovingAverage
    ChangeFromTwoHundreddayMovingAverage
    ChangeFromYearHigh
    ChangeFromYearLow
    ChangePercentRealtime
    ChangeRealtime
    Change_PercentChange
    ChangeinPercent
    Commission
    Currency
    DaysHigh
    DaysLow
    DaysRange
    DaysRangeRealtime
    DaysValueChange
    DaysValueChangeRealtime
    DividendPayDate
    DividendShare
    DividendYield
    EBITDA
    EPSEstimateCurrentYear
    EPSEstimateNextQuarter
    EPSEstimateNextYear
    EarningsShare
    ErrorIndicationreturnedforsymbolchangedinvalid
    ExDividendDate
    FiftydayMovingAverage
    HighLimit
    HoldingsGain
    HoldingsGainPercent
    HoldingsGainPercentRealtime
    HoldingsGainRealtime
    HoldingsValue
    HoldingsValueRealtime
    LastTradeDate
    LastTradePriceOnly
    LastTradeRealtimeWithTime
    LastTradeTime
    LastTradeWithTime
    LowLimit
    MarketCapRealtime
    MarketCapitalization
    MoreInfo
    Name
    Notes
    OneyrTargetPrice
    Open
    OrderBookRealtime
    PEGRatio
    PERatio
    PERatioRealtime
    PercebtChangeFromYearHigh
    PercentChange
    PercentChangeFromFiftydayMovingAverage
    PercentChangeFromTwoHundreddayMovingAverage
    PercentChangeFromYearLow
    PreviousClose
    PriceBook
    PriceEPSEstimateCurrentYear
    PriceEPSEstimateNextYear
    PricePaid
    PriceSales
    SharesOwned
    ShortRatio
    StockExchange
    Symbol
    TickerTrend
    TradeDate
    TwoHundreddayMovingAverage
    Volume
    YearHigh
    YearLow
    YearRange
    symbol

[webapi-vim]: https://github.com/mattn/webapi-vim
