// java example for any object that requires an ID for every instance generated

// Author: enthye

public class IDGenerator {
    private static int idCount = 100000; // static field works independently of each instance
    private String id;
    
    public IDGenerator() {
        this.id = "ID" + this.idCount; // first instance has id tag "ID100000"
        idCount++; // next object will have "ID100001"
    }
    
    public String getID() {
      return this.id;
    }
}
