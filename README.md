# String
String&amp;StringBuffer&amp;StringBuilder
package mypackages;

public class StringsAndStringsbuilder {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		System.out.println("Method of Strings");
		String SI=new String("Hello world");
		System.out.println(SI.length());
		
		String sub=new String("Welcome");
		System.out.println(sub.substring(2));
		
		String s1="Papa";
		String s2="Mummy";
		System.out.println(s1.compareTo(s2));
		
		
		String s4="";
		System.out.println(s4.isEmpty());
		
		String s5="HEllo";
		System.out.println(s5.toLowerCase());
		
		String s6="Radhekrishna";
		System.out.println(s6.replace("krishna", "Shyma"));
		
		String s7="Radhekrishna";
		String s8="RadheShyma";
		System.out.println(s7.equalsIgnoreCase(s8));
		
		System.out.println("\n"+" Creating StingBuffer");
		StringBuffer s=new StringBuffer("Welcome to java!");
		s.append("Studies hards");
		System.out.println(s);
		
		s.insert(0, 'w');
		System.out.println(s);
		
		StringBuffer sb=new StringBuffer("HEllo");
		sb.replace(0, 2, "hel");
		System.out.println(sb);

		sb.delete(0, 1);
		System.out.println(sb);
		
		System.out.println("\n" +"String Builder");
		StringBuilder sb1=new StringBuilder("Happy");
		sb1.append("jounary");
		System.out.println(sb1);
		
		
		
		
	}

}


