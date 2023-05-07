using System;

public class RoastGenerator
{
    public static void Main(string[] args)
    {
        //optionally personalize
        Console.WriteLine("Ew who are you?");
        string name = Console.ReadLine();

        //create a start and multiple ends
        string start = ", you look like you don't know ";
        string[] ends = {"your abc's", 
            "your mama's real first name", 
            "how to tie your shoes"
        };

        //create a randomizer
        Random randObj = new Random();
        //get a random integer between 0 and the number of ends you have
        int index = randObj.Next(ends.Length);
        //concatenate name with start and the randomly chosen end
        string roast = name + start + ends[index];
        //set exceptions
        if(name == “Emmett”){
               
        }
        //print roast
        Console.WriteLine(roast);
    }
}
