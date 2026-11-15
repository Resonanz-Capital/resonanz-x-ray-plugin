# Choose the smallest useful analysis

## Clarify an upload

Use inspected evidence to explain what was found and ask one grouped, relevant
question. For example, if the tool recognizes dates and percentage-formatted returns
but no currency or cash-return meaning: "I found a dated return history. What currency
is it in, and are these reported returns or returns after subtracting cash?" Do not
ask those questions when the file or saved answers already settle them. If the date
format, selected table or first return's period is unclear, clarify that specific
issue using actual cells. Do not treat a guessed calendar as an observed fact.
If the importer proposes a calendar and first return's opening date, include those
assumptions in the existing import confirmation; do not ask the same questions
separately. Follow the connection's proposal and correction rules.

Keep partial answers with the retained original using the available tools. A user
answering "USD, after cash" need not repeat that answer when clarifying a date later.
Missing optional descriptions do not block import: "You can also add the strategy
or style, or leave those blank." Skip that offer if it was already declined or adds
no value. Readable report text can support a proposed detail for the selected fund;
it does not replace confirmed answers or supply numerical observations.

Present the proposed interpretation and any update/new choice through the connection's
confirmation workflow. A changed interpretation needs fresh confirmation. For scans
or unreadable tables, explain the actual extraction limitation and request a readable
table or spreadsheet; do not promise OCR or reconstruct missing numbers.

After confirmation, briefly acknowledge the investments and coverage and continue the
original analysis request. If only one calculation needs another convention, ask for
that convention without implying the whole file is unusable. Do not turn receipt of
a file or successful validation into a claim that calculations have completed.

## Select the analysis

Resolve the intended investment and inspect its validation, identity, units,
currency, frequency and coverage before selecting an analysis. Ask only about
ambiguities that affect the next calculation; unrelated warnings do not block
everything. Explain an issue in financial terms and recommend a resolution.
Missing observations remain missing unless the user explicitly requests and
confirms an available edit. A currency-label change is not a conversion.

Before interpreting price/NAV changes as total returns, establish whether the
history accounts for distributions and relevant corporate actions. A distributing
fund's NAV alone need not capture its investor return. If this affects the answer,
clarify the input meaning and use a supported representation; do not invent
adjustments or call an unadjusted price change total return. Unrelated descriptive
work can continue with the limitation stated.

Use current tool schemas, returned readiness and calculation metadata. Do not
maintain a second algorithm, frequency, calendar, benchmark or factor catalogue
in this guide. No universal currency/calendar guesses or manual annualization.
Do not add a readiness call before every straightforward calculation.
Missing cash or a benchmark column in an upload does not itself establish that a
calculation is unavailable. Follow the tool's preparation/default rules and explain
only the actual unmet requirement, without discussing internal reference sources.

| Objective | Useful first step | Possible follow-up |
| --- | --- | --- |
| Understand performance | Summary and a cumulative-return or drawdown view | Examine the period driving the finding |
| Understand losses | Drawdown depth, duration and recovery where returned | Compare recovery across investments |
| Understand exposures | Correlations or sensitivities, according to the question | Risk/return attribution if the user wants contributions |
| Understand a portfolio | Supported portfolio return/risk analysis using supplied allocations | Holding contributions or an explicitly requested allocation scenario |
| Understand change over time | Relevant supported rolling metric | Compare periods using consistent definitions |

These are examples, not a tool allowlist or a mandatory sequence. Do not equate
correlation, beta, portfolio weights and contribution. Preserve signed values,
units, factor labels and model samples from the result. Model residual/Alpha is
not proof of manager skill. No extra factor filtering or label rewriting here.

For a requested fuller assessment, add only relevant sections. Calendar-duration
rolling views such as 12 and 36 months can be useful when supported and covered;
the server's defaults and validation still apply. Do not shorten a requested
window silently or fill unavailable periods to complete a chart. Keep valid
descriptive results when another section is unavailable.

For a rolling view, make the lookback visible alongside the result: window length
and unit, return frequency, result frequency and relevant annualization, using
the tool's actual metadata. Put the window in the chart label and identify a
default when used. For example: '3-month rolling annualized volatility, calculated
from daily returns and updated daily.' If verified history cannot support the
requested/default window, explain the limitation, recommend a shorter window
suited to the metric and ask the user to choose before changing it. Do not ask
again when the user already specified a supported window. One monthly observation
can give a one-month return but cannot support sample volatility or regression;
do not offer an unsuitable shorter window merely to produce a chart.
A single eligible rolling endpoint is one trailing statistic, not evidence of
a trend or stability over time.

Follow pagination before claiming complete rankings or coverage. If the user
needs only a bounded view, identify that subset. Do not fetch every chart or
all history simply because the tools are available. Submit heavy analyses
sequentially as instructed by the connection.

For portfolios, explain the applicable allocation timing and rebalancing meaning
when material, using the prepared result rather than inventing a shift. A scenario
is historical analysis, not an executed trade. If an operation is unsupported,
state that specific limitation without declaring the entire app unable to analyze
portfolios.
