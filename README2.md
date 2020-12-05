<p align="center">
    <a href="http://medfast.ml/s3//" target="_blank">
        <img src="https://github.com/lucymakori/README/blob/main/medfast_logo.png" width="400" alt="medfast" />
    </a>
</p>

Medfast payment production module
------------
Payment system for issuing and printing bank cheques,record management,scheduling events and keep accounting records.


Installation
------------

- clone this repository.
- install dependencies using yarn install or npm install.
- Start development server using yarn dev or npm run dev.

### Directory Structure

```
accounting
    cashledger/         contains cashbook Hypertext Markup Language file
    cashstore/          contains cashbook store Hypertext Markup Language file
    ledger-accounts/    contains ledger accounts Hypertext Markup Language file
    ledger-ref/         contains ledger refference Hypertext Markup Language file   
banking
    account             contains bank accounts Hypertext Markup Language file
    banks               contains banks Hypertext Markup Language file
    branch              contains bank branches Hypertext Markup Language file
calender
    dates               contains date schedules Hypertext Markup Language file
fonts                   contains project fonts 
login                   contains login modules Hypertext Markup Language file  
nuxt                    contains project fuctionality folder
payment
    batch/              contains cheque batch Hypertext Markup Language file
    cheques/            contains cheques Hypertext Markup Language file
    create/             contains batch create Hypertext Markup Language file
settings 
    change/             contains password settings Hypertext Markup Language file
vendor                  contains User Interface kit libraries
index.html              contains files that loads the app

```

