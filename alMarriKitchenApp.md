## Existing reports
- [ ] Line space adjustment in crystal reports for the above reports ***on progress by Munawar***

## CUSTOMER MASTER
- [x] Option to add TRN NUMBER of the customers, this TRN NUMBER to be appeared under INVOICE of the same customer.  ***done***

## PRODUCT
- [x] Only show the PRODUCT NAME when we browse and insert PRODUCTS from the list under Quotation or Site visit module. ***done***

- [ ] Increase and decrease the stock qty during purchase and sale

Now it is displaying entire field of the product (i.e: product name, category, vendor, price, qty and description etc..)

## QUOTATION
- [x] REMARKS… set the below wording as default (if required we will amend).
      Dear Sir / Madam,
      Thank you for your enquiry and we are pleased to offer you the following. ***done***
      
- [ ] LOGO IMAGE TO BE CHANGED… Background shade is appearing.. Please insert the new logo image file. 

- [x] Provide an option to change the quotation sender name and address, it is required for sending quotation by multiple sales man (each sales man required to send their offer by their own name and number), keep the present one as default but in editable mode ***done***

- [x] Provide a SAVE AS option, to use the same quotation for another customers if the requirement / specification is same (only change the TO Address and send to the new customer). ***done***

it is reduce the duplicate work…. Now system allows to edit the old quotationand change the customer name, but after saving old quotation is replacing with the new one (after saving old quotation no more accessible… disappear from the list). So we need like a save as or save as template option. 

## INVOICE
- [ ] LOGO IMAGE TO BE CHANGED… Background shade is appearing.. Please insert the new logo image file. 
- [x] If one invoice is deleted, then unable to recreate the invoice for the same project again (Project number is not showing under new invoice screen). ***Done***
- [ ] INVOICE DELETION or REVERSAL: Please restrict the invoice and receipt delete/reverse permission to administrator only…

If Administrator want to delete the payment received invoice, then receipt voucher must reverse first,, then only allow to reverse the invoice. … otherwise we will have issues in the invoice outstanding part.. please check and do the needful. 

- [x] TRN NUMBER is mandatory: let it pick from the customer master  ***Done***
- [x] UAE VAT is 5%, please therefore make default is 5% (instead of 10%)  ***Done***
- [ ] Please provide a field to enter LPO NUMBER (optional)
- [ ] While saving invoice please provide an option to save as 1) DRAFT INVOICE 2) CONFIRMED INVOICE

DRAFT INVOICE can be edited or changed until saving as CONFIRMED INVOICE. After saving as CONFIRMED INVOICE then it cannot be edited or reversed (except the administrator)
- [ ] PAGE FOOTER records only appear in end of the INVOICE, now it is appearing in all page. (if invoice having more than 1 page let it appear only the last page)

## RECIEPT
- [ ] Receipt start with Customer Number . Once the customer is selected, his invoice(s) is/are selected from the datalist.
- [ ] Let Payer name auto-populated from Customer Master 
- [ ] In Payment History section, let it display all the unpaid invoices of the particular customer.
- [ ] Paid invoice numbers are not showing in the receipt(Show the invoice(s) number for which the reciept isn generated) 
- [ ] Make receipt number auto-numbering	
- [ ] Change the word CASH to Payment Mode  (screenshot attached for reference)
- [ ] There is no option to REPRINT the saved receipt again, now we need to go to edit mode and then click on the SAVE button to print again, which is totally wrong (receipt cannot be edited by normal user).

## Payroll
- [ ] Bulk payroll -select employees by checkbox, (Base pay - unpaid leave - previous advance deduction + overtime) 
- [ ] Leave entry - Select employee, enter leave date, calculate number of days, select leave type (paid, unpaid or sick)
- [ ] Advance payment- Select employee, Enter amount, select repayment mode (1. deduct from coming month 2. deduct from 3/6/12 months)
- [ ] Overtime - Select employee, enter number of hours
- [ ] Employee report for selected year - Number of leaves - paid,unpaid,sick. , Remaining leaves, Total overtime, etc.

Leave entries are done for the current month. If an employee is on leave from 25th to 31st of may and 1st to 5th of June, then it is marked as one leave of 11 days. Out of this 11 days if he only has 5 days of paid leave, then it is marked as 5 days paid till 30th May and 6 days unpaid leave from 31st to 5th.

## PURCHASE INVOICE
- [ ] SUPPLIER MASTER: create a supplier master to enter the supplier name and details (same as customer master)
- [ ] Provide an option to select the PROJECT NUMBER under PURCHASE INVOICE/NEW ITEM tab. So will know this item is purchased for the particular project. Also later we can check how much materials purchased for the same project. 
- [ ] TAX 5% to be auto-populated (same as our SALES INVOICE),  Keep this amount editable.. because very rare invoices we are getting without TAX

## Delivery Note
- [ ] List of confirmed invoices with a view button to generate delivery note

Same as invoice without the price details
## Costing module
**Collecting data. Will update soon...**
