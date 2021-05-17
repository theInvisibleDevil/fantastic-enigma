# fantastic-enigma
My first Repository



package lec.pkg14.string.methods;


public class Lec14StringMethods {


    public static void main(String[] args) {
        String name = "Hammad";         //Declaring String
        
            //using length method to calculate the length of String
        int length = name.length();
        System.out.println(length);
        
            //using LowerCase method to print the string in LowerCase
        String lCase = name.toLowerCase();
        System.out.println(lCase);
        
            //using UpperCase method to print the string in UpperCase
        String uCase = name.toUpperCase();
        System.out.println(uCase);
        
            //subString method - Returns a Substring from start to the end. => substring(3) will return mad
        System.out.println(name.substring(3));
        
        //subString(int start, int end) method - Returns a subString from Start Index to the end Index. Start index is included and end is Excluded.
        System.out.println(name.substring(1,4));
        
        //name.replace('old char', 'new char') - Replacing A character with another character. If i replace m with n in my name hammad, it will return hannad after replacement.
        System.out.println(name.replace('m','n'));
        //name.replace('target', 'replacement') - Replacing a target with another character or many characters. If i replace Ham with Ah in my name hammad, it will return Ahmad after replacement.
        System.out.println(name.replace("Ham", "Ah"));
        
        //name.startsWith( ) - returns true if name starts with "Ham" and false if not.
        System.out.println(name.startsWith("Ham"));
        
        //name.endsWith( ) - returns true if name ends with "ad" and false if not.
        System.out.println(name.endsWith("ad"));
        
        //name.charAt(2) - return character at a given index position. m in this case will be returned
        System.out.println(name.charAt(2));
        
        //name.indexOf(s) - returns the index of the given string. 
        System.out.println(name.indexOf("ma"));
        
        //name.indexOf("s", 3) - returns the index of the given String Starting from the index 3
        System.out.println(name.indexOf("m", 0));
        
        
    }
    
}
