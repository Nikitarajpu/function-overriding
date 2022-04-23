# function-overriding
using System;
using System.IO;
using System.Linq;
using System.Collections.Generic;


     class Program 
    {
    	public virtual void showinfo()
    	{
    		Console.WriteLine("Base class method");
    	}
    }
    class B:Program
    {
    	public override void showinfo()
    	{
    		Console.WriteLine("Deriver class method");
    	}
    
        public static void Main() 
        {
           B b1=new B();
           b1.showinfo();
        }
    }
    
    
