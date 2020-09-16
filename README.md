# donkey
1	public class Donkey {
2	  //egenskaber
3	  int donkeyHeight;
4	  String donkeyName;
5	  int donkeyAge;
6	
7	  //konstruktør
8	  Donkey(int height, String name, int age){
9	    donkeyHeight = height;
10	    donkeyName = name;
11	    donkeyAge  = age;
12	
13	  }
14	
15	  //adfærd
16	    public void myDonkey() {
17	      System.out.println("my donkey is " + donkeyAge );
18	    }
19	
20	    public static void main(String[] args) {
21	//  Donkey myDonkey = new Donkey();
22	
23	      //references
24	      Donkey[] arrayOfDonkey = new Donkey [10];
25	      Donkey donkey1 = new Donkey(150,"Morten",19);
26	       Donkey donkey2 = new Donkey (250,"Heimer",69);{
27	     
28	      arrayOfDonkey[1] = donkey1;
29	      arrayOfDonkey[2] = donkey2;
30	           donkey2.myDonkey();
31	        
32	      for(int i = 0; i<arrayOfDonkey.length;i++){
33	        if(arrayOfDonkey[i]!= null){
34	        
35	        // data for Donkey
36	        arrayOfDonkey[i].myDonkey();
37	        
38	      }
39	
40	     // myDonkey.myDonkey();
41	    }
42	
43	
44	}
45	}
46	}
