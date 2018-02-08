/**
 * A class that holds a dog's name and can make it speak.
 * @author Jonathon Webster
 * @version 2/8/18
 */
public class Dog
{
    private String name;
    /**
     * Constructor -- store name
     * @param name
     */
    public Dog(String name)
    {
        this.name = name;
    }

    /**
     * Returns the dog's name
     * @return name
     */
    public String getName()
    {
        return name;
    }

    /**
     *  Returns a string with the dog's comments
     *  @return "woof"
     */
    public String speak()
    {
        return "woof";
    }
}
