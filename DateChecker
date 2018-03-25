// Simple date format checker in Java

package testcodehere;

import java.text.ParseException;
import java.text.SimpleDateFormat;

/**
 * @author enthye
 */

public class Test {
    
    // e.g. isInDateFormat("yyyy-MM-dd'T'hh:mm", "2018-03-25T07:30") == true
    // months = MM, minutes = mm
    
    // date format in ISO-8601
    public boolean isInDateFormat(String dateFormat, String dateInput) {
        SimpleDateFormat date = new SimpleDateFormat(dateFormat);
        date.setLenient(false);
        try {
            date.parse(dateInput);
	} catch (ParseException pe) {
            return false;
	}
        
        return true;
    }
}

