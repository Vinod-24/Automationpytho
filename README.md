package automationPack;

import org.openqa.selenium.WebDriver;
import org.openqa.selenium.chrome.ChromeDriver;

public class FirstAutomationProgram 
{
	public static void main(String[] args) 
	{
		System.setProperty("webdriver.chrome.driver", 
				"D:\\Back-up Data\\Desktop-Backup\\Pavan Velo\\Automation Batch Material\\Downloads\\chromedriver_win32\\chromedriver.exe");	
	    
		WebDriver driver = new ChromeDriver();
		
		driver.get("https://www.facebook.com/");
			
		
	}

}
