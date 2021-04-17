# Java-Interfaces---Exercise
Topics: 
Composition of entities 
Composition of services 
Interfaces 
Inversion injection / control dependency


# Statement of exercise:
A company wants to automate the processing of its contracts. The processing of a contract consists of generating the installments to be paid for that contract, based on the desired number of months.

The company uses an online payment service for payment in installments. Online payment services typically charge monthly interest, as well as a payment fee. For now, the service hired by the company is Paypal, which charges a simple interest of 1% on each installment, plus 2% of the payment fee.

The program will be read the data of a contract (contract number, contract date, and total contract value). Then, the program should read the number of months of the contract installment, and from there generate the records of the installments to be paid (date and amount), with the first installment to be paid one month after the contract date, the second installment two months after the contract and so on. 
