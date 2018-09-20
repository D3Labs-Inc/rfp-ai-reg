# Title

 Internal Revenue. PART 51—BRANDED PRESCRIPTION DRUG FEE


# ID

 CFR-2018-title26-vol19.Pt. 51


# Structured Analysis Summary

| Type        | Values                                                                                                                                                                                   |
|:------------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Money       | [(310000.0, 'USD'), (10000.0, 'USD'), (400000001.0, 'USD'), (100000.0, 'USD'), (0.0, 'USD'), (5000000.0, 'USD'), (200000.0, 'USD'), (20000.0, 'USD')]                                    |
| Constraints | ['at least', 'within', 'less than', 'after', 'more than', 'no later than', 'equal to', 'before']                                                                                         |
| Duration    | ['4 quarter', '6.0 month', '2 year', '3 year']                                                                                                                                           |
| Condition   | ['until', 'when', 'subject to', 'if']                                                                                                                                                    |
| Entities    | ['Refund', 'Information', 'Tax', 'Defense', 'Applicability', 'Health', 'Method', 'Overview', 'Dispute', 'Request', 'Program', 'Agency', 'Medicaid', 'Entity', 'Veterans Affairs', 'Fee'] |
| Date        | ['2017-07-24', '6302-01-01', '2014-07-28']                                                                                                                                               |


# Structured Analysis With Context

 


## Money

| Money                | Context                                                                                                                                                                                                                                                                                                                                                                                                       |
|:---------------------|:--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| (5000000.0, 'USD')   | (c) Section 9008(b)(4) sets an applicable fee amount for each year, beginning with 2011, that will be apportioned among covered entities with aggregate branded prescription drug sales of over $5 million to government programs or pursuant to coverage under such programs.                                                                                                                                |
| (5000000.0, 'USD')   | Entity A is a manufacturer with gross receipts of more than $5 million from branded prescription drugs sales in 2011.                                                                                                                                                                                                                                                                                         |
| (0.0, 'USD')         | For the 2013 fee year, Entity A is also liable for the adjustment amount described in &#167;&#8201;51.5(e) for the difference between its 2012 fee computed using sales data from the 2010 sales year, which is $0, and what the 2012 fee would have been using sales data from the 2011 sales year.                                                                                                          |
| (0.0, 'USD')         | Therefore, for the 2014 fee year, Entity A will receive an adjustment amount for the difference between its 2013 fee computed using sales data from the 2011 sales year, and what the 2013 fee would have been using sales data from the 2012 sales year, which is $0.                                                                                                                                        |
| (400000001.0, 'USD') | The term sales taken into account means branded prescription drug sales after application of the percentage adjustment table in section 9008(b)(2) (relating to annual sales less than $400,000,001).                                                                                                                                                                                                         |
| (310000.0, 'USD')    | For example, if HCPCS code JXXXX contains three drugs with a total of $310,000 sales reported by manufacturers to CMS for the sales year, and $100,000 was reported for Drug A, $200,000 was reported for Drug B, and $10,000 was reported for Drug C, the proportion of sales attributed to each NDC will be 32.26 percent for Drug A, 64.52 percent for Drug B, and 3.22 percent for Drug C; and            |
|                      |             (B) For each NDC, multiply the product of the annual weighted ASP and the total allowed billing units paid by Medicare Part B for the HCPCS code by the proportion of sales calculated in paragraph (c)(4)(ii)(A) of this section to determine the sales reportable to the IRS (that is, percentage &#215; (annual weighted ASP &#215; allowed units) = total sales reported to IRS for the NDC). |
| (100000.0, 'USD')    | For example, if HCPCS code JXXXX contains three drugs with a total of $310,000 sales reported by manufacturers to CMS for the sales year, and $100,000 was reported for Drug A, $200,000 was reported for Drug B, and $10,000 was reported for Drug C, the proportion of sales attributed to each NDC will be 32.26 percent for Drug A, 64.52 percent for Drug B, and 3.22 percent for Drug C; and            |
|                      |             (B) For each NDC, multiply the product of the annual weighted ASP and the total allowed billing units paid by Medicare Part B for the HCPCS code by the proportion of sales calculated in paragraph (c)(4)(ii)(A) of this section to determine the sales reportable to the IRS (that is, percentage &#215; (annual weighted ASP &#215; allowed units) = total sales reported to IRS for the NDC). |
| (200000.0, 'USD')    | For example, if HCPCS code JXXXX contains three drugs with a total of $310,000 sales reported by manufacturers to CMS for the sales year, and $100,000 was reported for Drug A, $200,000 was reported for Drug B, and $10,000 was reported for Drug C, the proportion of sales attributed to each NDC will be 32.26 percent for Drug A, 64.52 percent for Drug B, and 3.22 percent for Drug C; and            |
|                      |             (B) For each NDC, multiply the product of the annual weighted ASP and the total allowed billing units paid by Medicare Part B for the HCPCS code by the proportion of sales calculated in paragraph (c)(4)(ii)(A) of this section to determine the sales reportable to the IRS (that is, percentage &#215; (annual weighted ASP &#215; allowed units) = total sales reported to IRS for the NDC). |
| (10000.0, 'USD')     | For example, if HCPCS code JXXXX contains three drugs with a total of $310,000 sales reported by manufacturers to CMS for the sales year, and $100,000 was reported for Drug A, $200,000 was reported for Drug B, and $10,000 was reported for Drug C, the proportion of sales attributed to each NDC will be 32.26 percent for Drug A, 64.52 percent for Drug B, and 3.22 percent for Drug C; and            |
|                      |             (B) For each NDC, multiply the product of the annual weighted ASP and the total allowed billing units paid by Medicare Part B for the HCPCS code by the proportion of sales calculated in paragraph (c)(4)(ii)(A) of this section to determine the sales reportable to the IRS (that is, percentage &#215; (annual weighted ASP &#215; allowed units) = total sales reported to IRS for the NDC). |
| (100000.0, 'USD')    | For example, if the total amount reimbursed is $100,000, and the Medicaid amount reimbursed is $20,000, then the percentage is 20 percent.                                                                                                                                                                                                                                                                    |
| (20000.0, 'USD')     | For example, if the total amount reimbursed is $100,000, and the Medicaid amount reimbursed is $20,000, then the percentage is 20 percent.                                                                                                                                                                                                                                                                    |


## Constraints

| Constraints   | Context                                                                                                                                          |
|:--------------|:-------------------------------------------------------------------------------------------------------------------------------------------------|
| at least      | a group of two or more persons, including at least one person that is a covered entity, that                                                     |
| within        | subject to tax under section 881 is included within a group under section 52(a) or 52(b); and                                                    |
| more than     | A is a manufacturer with gross receipts of more than $5 million from branded prescription drugs sales in                                         |
| before        | any gross receipts from branded prescription drug sales before  or after 2011.                                                                   |
| after         | receipts from branded prescription drug sales before or after  2011.                                                                             |
| after         | adjustment amount described in &#167;&#8201;51.5(e) for Entity A. after                                                                          |
| after         | Accordingly, Entity A is not a covered entity  after  the 2014 fee year.                                                                         |
| within        | The term designated entity means the person  within a controlled group that is designated to act                                                 |
| within        | entity is the agent for the group ( within  the meaning of &#167;&#8201;1.1502-77 of this title).                                                |
| after         | or (ii) Any drug for any sales year after the calendar year in which the FDA approved                                                            |
| before        | section 45C credit was allowed for the drug before , in the same year as, or after                                                               |
| after         | or (ii) Any drug for any sales year after the calendar year in which the FDA approved                                                            |
| after         | taken into account means branded prescription drug sales after application of the percentage adjustment table in section                         |
| less than     | table in section 9008(b)(2) (relating to annual sales less than  $400,000,001).                                                                  |
| after         | the dispute resolution process (described in &#167;&#8201;51.7) and, after applying appropriate due diligence, will provide this list            |
| after         | by the PDE submission deadline (within 6 months after the end of the sales year) and that                                                        |
| within        | (A) Any direct and indirect remuneration (DIR) ( within the meaning of paragraph (b)(2)(ii) of this section),                                    |
| within        | Report means the report containing any DIR ( within the meaning of paragraph (b)(2)(ii) of this section)                                         |
| equal to      | entity's allocated fee for any fee year is equal to an amount that bears the same ratio to                                                       |
| after         | entity's branded prescription drug sales taken into account after application of &#167;&#8201;51.5(a)(4); (4) The aggregate branded prescription |
| no later than | its final determination with respect to error reports no later than the time the IRS provides a covered entity                                   |
| after         | the IRS will not accept an error report after the end of the dispute resolution period or                                                        |
| after         | the IRS will not accept an error report after the end of the dispute resolution period or                                                        |
| no later than | entity its final fee calculation for that year. no later than                                                                                    |
| after         | entity's branded prescription drug sales taken into account after application of &#167;&#8201;51.5(a)(4); (5) The aggregate branded prescription |
| after         | a change in data reported by the Agencies after resolution of error reports, including a change in                                               |
| within        | amount of the fee for any fee year within three years of September 30th of that fee                                                              |
| after         | this section, &#167;&#167;&#8201;51.1 through 51.10 apply on and after  July 28, 2014.                                                           |
| after         | (b) Section 51.2(e)(3) applies on and  after  July 24, 2017.                                                                                     |
| after         | This section applies on and  after  July 28, 2014.                                                                                               |


## Duration

| Duration   | Context                                                                                                                                                                                                                                                                                                                                                                                    |
|:-----------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 2 year     | The term sales year means the second calendar year preceding the fee year.                                                                                                                                                                                                                                                                                                                 |
| 6.0 month  | CMS will only include PDE data that Part D sponsors have submitted by the PDE submission deadline (within 6 months after the end of the sales year) and that CMS has approved for inclusion in the Part D payment reconciliation.                                                                                                                                                          |
| 4 quarter  | (2) For any covered entity identified in the first five (or six) digits of an NDC during any of the four quarters of a sales year, CMS will use the following methodology to derive the sales figures that account for third-party payers, such as Medicare Part B:                                                                                                                        |
|            |             (i) Report total dollars per NDC for AMP minus URA multiplied by the units reported by a state or states.                                                                                                                                                                                                                                                                      |
| 2 year     | An adjustment amount reflects the difference between the allocated fee determined for the covered entity in the immediately preceding fee year, using data from the second calendar year preceding that fee year, and what the allocated fee would have been for that entity for the immediately preceding fee year using data from the calendar year immediately preceding that fee year. |
| 3 year     | The IRS must assess the amount of the fee for any fee year within three years of September 30th of that fee year.                                                                                                                                                                                                                                                                          |


## Condition

| Condition   | Context                                                                                                             |
|:------------|:--------------------------------------------------------------------------------------------------------------------|
| subject to  | term prescription drug means any drug that is subject to  section 503(b) of the FFDCA.                              |
| subject to  | (related to controlled groups)&#8212; (i) A foreign entity subject to tax under section 881 is included within a    |
| if          | as being a member of a controlled group if it is a member of the group on                                           |
| until       | drug sales and continues each subsequent fee year until there are no remaining branded prescription drug sales      |
| if          | (iii) Filing an error report for the group, if applicable, as described in &#167;&#8201;51.7; and (iv) Paying       |
| if          | as provided in paragraph (f)(2)(ii) of this section, if a controlled group does not select a designated             |
| when        | the NDC or the first six numeric characters when  the available five-character code combinations are exhausted.     |
| if          | For example,  if HCPCS code JXXXX contains three drugs with a                                                       |
| if          | For example,  if the total amount reimbursed is $100,000, and the                                                   |
| when        | total amount paid (net of refunds and rebates, when they are associated with a specific NDC) for                    |
| if          | determine a covered entity's total fee by applying, if applicable, the adjustment amount described in paragraph (e) |
| if          | (4) For a mathematical calculation error, the spec if ic calculation element(s) that the entity disputes and        |
| if          | (4) For a mathematical calculation error, the spec if ic calculation element(s) that the entity disputes and        |
| if          | (4) For a mathematical calculation error, the spec if ic calculation element(s) that the entity disputes and        |
| if          | Even  if a covered entity did not file an error                                                                     |
| if          | Accordingly,  if a controlled group's fee is not paid, the                                                          |
| subject to  | 6321, and 6331), enforced (section 7402 and 7403), subject to  examination and summons (section 7602), and          |
| subject to  | 6321, and 6331), enforced (section 7402 and 7403), subject to  examination and summons (section 7602), and          |
| if          | as defined in &#167;&#8201;31.6302-1(h)(4)(i) of this title, as if  the fee were a depository tax.                  |


## Entities

| Entities         | Context                                                                                                             |
|:-----------------|:--------------------------------------------------------------------------------------------------------------------|
| Overview         | Overview .                                                                                                          |
| Health           | Medicare and Medicaid Services of the Department of Health and Human Services (CMS); (2) The Department of          |
| Veterans Affairs | and Human Services (CMS); (2) The Department of Veterans Affairs  (VA); and                                         |
|                  |             (3) The Department of Defense (DOD).                                                                    |
| Defense          | Veterans Affairs (VA); and (3) The Department of Defense  (DOD).                                                    |
| Entity           | Entity A is a manufacturer with gross receipts of                                                                   |
| Entity           | Entity A does not have any gross receipts from                                                                      |
| Entity           | Entity A is a covered entity beginning in 2011                                                                      |
| Entity           | Entity A continues to be a covered entity for                                                                       |
| Defense          | prescription drugs are procured by the Department of Defense ; and                                                  |
|                  |             (6) The TRICARE retail pharmacy program.                                                                |
| Information      | Information  requested from covered entities.                                                                       |
| Defense          | (f) Department of  Defense .                                                                                        |
| Fee              | Fee  calculation.                                                                                                   |
| Medicaid         | If CMS has  Medicaid state supplemental rebate information for a sales year,                                        |
| Request          | not file Form 843, Claim for Refund and Request for Abatement, to receive this amount owed to                       |
| Program          | entity's branded prescription drug sales, by NDC, by Program ; (3) The covered entity's branded prescription drug   |
| Dispute          | Dispute  resolution process.                                                                                        |
| Agency           | and an explanation of why the IRS or Agency should use the proposed corrected data instead; (8)                     |
| Program          | entity's branded prescription drug sales, by NDC, by Program ; (4) The covered entity's branded prescription drug   |
| Tax              | Tax  treatment of fee.                                                                                              |
| Refund           | Refund  claims.                                                                                                     |
| Request          | made on Form 843, &#8220;Claim for Refund and Request for Abatement,&#8221; in accordance with the instructions for |
| Applicability    | Applicability  date.                                                                                                |
| Method           | Method  of paying the branded prescription drug fee.                                                                |


## Date

| Date       | Context                                                                                                                                                                                                                                                                      |
|:-----------|:-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 6302-01-01 | The fee must be paid by electronic funds transfer as required by &#167;&#8201;51.6302-1.                                                                                                                                                                                     |
| 2014-07-28 | (a) Except as otherwise provided in this section, &#167;&#167;&#8201;51.1 through 51.10 apply on and after July 28, 2014.                                                                                                                                                    |
| 2017-07-24 | (b) Section 51.2(e)(3) applies on and after July 24, 2017.                                                                                                                                                                                                                   |
| 6302-01-01 | Under the authority of section 6302(a), the fee imposed on branded prescription drug sales by section 9008 and &#167;&#8201;51.5 must be paid by electronic funds transfer as defined in &#167;&#8201;31.6302-1(h)(4)(i) of this title, as if the fee were a depository tax. |
| 2014-07-28 | This section applies on and after July 28, 2014.                                                                                                                                                                                                                             |


