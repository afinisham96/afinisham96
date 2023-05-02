http://10.10.5.37:8083/additional-document-upload?f4bcaeac97da7f9c925b8c09304972e5&02PFON20000000000508

As conversed, this is the method how to capture CCRIS commitment accurately.

With refer to attached CTOS report screenshot,

1. For facility NOT credit card (CRDTCARD), if the installment amount column (RED highlighted column) in the CCRIS report has value, system will directly take the instalment amount as the customer's CCRIS commitment.

2. For facility is credit card (CRDTCARD), the installment amount column (RED highlighted column) in the CCRIS report will always reported as zero. Therefore, system has to use formula as per below with conditions to determine the CCRIS commitment.
Formula = 5% x CC Total outstanding balance (RM) [Green highlighted column)

Conditions:++
(a) Only take credit card CCRIS Commitment for NOT AEON CC, which is facility is CRDTCARD AND "Lender Type" column (BLUE highlighted column) must NOT be "OWN" (PURPLE highlighted column)
(b) If CC total outstanding balance is < RM50, CCRIS commitment amount will be as per CC total outstanding balance. Eg: cc total o/s balance is RM40, CCRIS commitment is RM40.
(c) If CC total outstanding balance is >= RM50, but <= RM1,000, CCRIS commitment amount will be RM50. Eg: cc total o/s balance is RM800, CCRIS commitment is RM50
(d) If CC total outstanding balance is >RM1,000, CCRIS commitment amount will be 5% of CC total o/s balance. Eg: cc total o/s balance is RM1,200, CCRIS commitment is RM60

3. For facility NOT credit card (CRDTCARD), if the installment amount column (RED highlighted column) in the CCRIS report is BLANK, system will use AEON's internal formula as per attached document named "Total Commitment Revision 1.7 (latest revise)"

4. For joint loan, which is Capacity column is "JOINT / PARTNER", CCRIS commitment amount captured need to divide by 2.
