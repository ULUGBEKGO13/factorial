# 	public class Program
	{
	static double factorial(int x)
	{
		double j = 1;
		for(int i = 2; i<x; i++)
		{
			j = j*i;
		}
		return j;
	}
	public static void Main(x)
	{
		int[]myArr = new int[52];
		for(int i = 1; i<51; i++)
		{
			myArr[i] = i;
			Console.WriteLine(myArr[i]);
		}
		for(int i1 = 1; i1 < 51; i1++)
		{
			for(int i2 = i1 + 1; i2<51; i2++)
			{
				for(int i3 = i2+1; i3< 51; i3++)
				{
					for(int i4 = i3 + 1; i4 <51; i4++)
					{
						for(int i5 = i4 + 1; i5<51; i5++)
						{
							for(int i6 = i5 + 1; i6<51; i6++)
							{
								for(int i7 = i6 + 1; i7<51; i7++)
								{
									
								}
							}
						}
					}
				}
			}
		}
	}
	Console.WriteLine(factorial(52)/(factorial(52 - 3) * factorial(3)));
