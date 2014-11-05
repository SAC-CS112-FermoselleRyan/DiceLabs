DiceLabs
========
import java.sql.Date;

import java.util.*;

import java.util.Scanner;

import java.math.*;

import java.util.Random;


public class DiceGame{
	public int sides;
	
	public DiceGame(){
		sides = 6;
		
	}
	public DiceGame(int side){
		this.sides=sides;
		
		
	}
	public int roll(){
		int roll=0;
		Random generator = new Random();
		roll = Math.abs(generator.nextInt()%sides+1);
		return roll;
	}
	
	
}
