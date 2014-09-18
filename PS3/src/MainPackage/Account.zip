package MainPackage;

import java.util.Date;
public class Account {

	private int id = 0; 
	
	private double balance = 0;
	
	private double annualInterestRate = 0; 
	
	private Date dateCreated;

	public Account(){
		
		this.id = 0;
		this.balance = 0;
		this.annualInterestRate = 0;
	}
	public Account(int id, double balance){
	this.id = id;
	this.balance=balance;}
	
	public int getId() {
		return id;
	}
	public void setId(int id) {
		this.id = id;
	}
	public double getBalance() {
		return balance;
	}
	public void setBalance(double balance) {
		this.balance = balance;
	}
	public double getAnnualInterestRate() {
		return annualInterestRate;
	}
	public void setAnnualInterestRate(double annualInterestRate) {
		this.annualInterestRate = annualInterestRate;
	}
	public Date getDateCreated() {
		return dateCreated;}
	
	double getMonthlyInterestRate(){
		return (annualInterestRate/(12));}
	 
	double withdraw(double Amount){
		return(balance = balance - Amount);
	}
		
	double deposit(double Amount){
		return (balance = balance + Amount);
	}
}