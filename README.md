using System;
using System.Collections.Generic;
using System.Text;
using System.Linq;
using System.Threading.Tasks;
using static System.Console;

public class Maze
{
 private string[,] grid;
 //private int size;

// public Maze(int n) 
  //{
    
  //}
 private void Initialize( )
  {
		string[,] grid = {
			{ "-", "-", "-", "-", "-", "-", "-", "-" },
      { "|", "", "|", "=", "=", "=", "=", "|" },
			{ "-", "-", "-", "=", "=", "=", "=", "|" },
      { "-", "-", "=", "=", "=", "=", "=", "|" },
			{ "|", "|", "=", "=", "=", "=", "=", "|" },
      { "-", "-", "=", "=", "=", "=", "=", "|" },
			{ "|", "=", "=", "=", "=", "=", "=", "|" },
			{ "-", "-", "-", "-", "-", "-", "-", "-" },
		};
		int rows = grid.GetLength(0);
		int cols = grid.GetLength(1);
		
  }                                       // Called by the constructor
// private void Create( )
 // {

 // }                                       // Called by the constructor
 private void DepthFirstSearch(int i, int j, bool[,] visited) 
  {
    for(int i = 0; i < rows; i++)
		{
			for(int j = 0; j < cols; j++)
			{
				string element = grid[i,j];
			}
		}
  }                                       // Called by Create
 //public void Print( ) 
  //{

  //}  
  static void Main(string[] args)
  {
    Maze m = new Maze();
    m.Initialize();
    //m.Create();
    //m.DepthFirstSearch();
    //m.Print();
    Console.ReadLine();
  }
} 
