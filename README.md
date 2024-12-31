# CHECKPOINT_BANK_ACCOUNT-
Object oriented programming (oop)  Creating a Bank Account.
class Account:
    def _init_(self, account_no: str, account_holder: str, account_balance: float):
        self.account_no = account_no
        self.account_holder = account_holder
        self.account_balance = account_balance 
        
        def deposit(self, amount: float):
        """Adds the specified amount to the account balance."""
        self.account_balance += amount
        print(f"Deposited {amount}. New balance: {self.account_balance}")
def withdraw(self, amount:float):
    if self.account_balance>=amount:
        self.account_balance-=amount
        print(f"withdrew {amount}. New balance: {self.account_balance}")
    else:
        print(f" Insufficient Balance! Current balance: {self.account_balance}") 

    def check_balance(self) -> float:
    print(f"Current_balance is {self.account_balance}")
    return self.account_balance

    #Instances

if __name__ == 'Personal_savings':
    # Create an instance of the Account class
    my_account = Account("123456789", 1000.0, "John Doe")
    
    # Perform transactions
    my_account.deposit(500)
    my_account.withdraw(300)
    my_account.check_balance()

   
