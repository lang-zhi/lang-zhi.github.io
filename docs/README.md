# 代码

 An awesome project.
 the fxxking new guy
 my first try to use this
 so can i use this?

>java中遍历21世纪的闰年并列为五个一行来输出
```
public class Rn 
{
	public static void main(String[] args)
	{
		int count=0;
		for(int i=2000;i<2100;i++)
		{
			if (i%4==0 && i%100!=0 ||i%400==0)
			{
					System.out.print(i+"\t");
					count++;
					if(count%5==0)
				{
					System.out.println("\n");
				}
			}
		}
	}

}
```