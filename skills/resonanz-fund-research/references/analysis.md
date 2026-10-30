# Choose the smallest useful analysis

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
