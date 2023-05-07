using System;

public class ShadowBox
{
    public static void Main(string[] args)
    {
        Console.WriteLine("Let's ShadowBox! \n Player 1 will point in a direction, Player 2 will try to look in a different direction. If they look the same direction, Player 1 wins!\n");
        Console.WriteLine("Wanna play? (type yes or no)");
        String playing = Console.ReadLine();
        int robo_points = 0;
        int user_points = 0;
        System.Threading.Thread.Sleep(1000);
        while(playing == "yes"){
            Random randomjosh = new Random();
            int whoGoes = randomjosh.Next(10);
            String[] directions = {"up", "down", "left", "right"};
            if(whoGoes >= 5){
                Console.WriteLine("You go first! (type right, left, up or down)");
                String user_direction = Console.ReadLine();
                int index = randomjosh.Next(directions.Length);
                String robo_direction = directions[index];
                if(user_direction == robo_direction){
                    Console.WriteLine("YOU WON!");
                    user_points++;
                }
                else{
                    Console.WriteLine("I WON. Better luck next time");
                    robo_points++;
                }
            }
            else{
                Console.WriteLine("I'll go first!");
                int index = randomjosh.Next(directions.Length);
                String robo_direction = directions[index];      
                Console.WriteLine("Your turn! (type right, left, up or down)");
                String user_direction = Console.ReadLine();
                if(user_direction == robo_direction){
                    Console.WriteLine("YOU WON!");
                    user_points++;
                }
                else{
                    Console.WriteLine("I WON. Better luck next time");
                    robo_points++;
                }
            }
            Console.WriteLine("That was fun! Wanna play again? (type yes or no)");
            playing = Console.ReadLine();
        }
        Console.WriteLine("Okay! Have a good one.");
        if(user_points != 0 || robo_points != 0){
            String score = "I got " + robo_points + " points!\nYou got " + user_points + " points!";
            Console.WriteLine(score);
        }
    }
}
