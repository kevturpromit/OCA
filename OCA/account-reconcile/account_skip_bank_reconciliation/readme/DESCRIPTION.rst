This module allows to exclude from bank statement reconciliation
all journal items of a specific reconcilable account.

Usually, you would want to that in accounts like the
`Goods Received Not Invoiced`, which are required to be reconcilable
to be able to have proper traceability in stock received but
their reconciliation is done using the `account_mass_reconcile` module.
