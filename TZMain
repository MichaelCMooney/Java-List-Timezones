import java.util.*;
import java.time.*;

public class TZMain
{
	public static void main(String args[])
	{
		TimeZones timeZones = new TimeZones();
    System.out.println("Pulling Time Zone List");
		timeZones.initiate();
	}

	private void initiate() 
	{
		List TZList = new ArrayList<>(ZoneId.getAvailableZoneIds());
		int TZIndex = 0;
		for (String zone : TZList)
			System.out.println(++TZIndex + ":" + zone);	
	}
}
