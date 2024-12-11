# new-one
class Main{
    public static void main(String[] args)
    {
        String orginalstring = "hello";
        String reversedstring = "";
        int index = orginalstring.length()-1;
        
        while(index >= 0)
        {
            reversedstring += orginalstring.charAt(index);
            index--;
        }
        System.out.println(orginalstring );
        System.out.println(reversedstring);
    }
}

program

