# hadi
public class Main
{
	public static void main(String[] args) 
	{
	
	String nama ="hadi eko styono"; 
	String address ="jl pemuda no 79, Pekanbaru, Riau";
    String[] hobi={"makan","minum","tidur"};
   
    String[] skill;
    skill =new String [2];
    skill[0]=" membaca    : 90";
    skill[1]=" menulis    : 80";
   
   
    boolean jawaban, a1,a2;
    a1=true;
    a2=false;
     
    
    System.out.println (" Biodata Pribadiku ");
    System.out.println ("___________________");
    System.out.println (" Nama       : " +nama);
    System.out.println (" Alamat     : " +address);
    System.out.println (" hobi       : " + hobi[2] );
    if(a2==false)System.out.println (" menikah    : belum");
    System.out.println (" skill     score");
    System.out.println (" -----     -----");
    
     System.out.println (skill[0]);
     System.out.println (skill[1]);

    //soal 3 
     System.out.println (" ----------------------");
     System.out.println (" soal 3");
     System.out.println (" ----------------------");
   char[] Kul = {'b', 'o','o', 't', 'c', 'a', 'm', 'p'};
    int Count = 0;	  
    for (int i=0; i<Kul.length; i++)
    {	      if (Kul[i] == 'o') Count++;	   }
    System.out.println("Jumlahf o yang ada di kalimat tersebut adalah: "+ Count);	
    
    //soal 5 
     System.out.println (" ----------------------");
     System.out.println (" soal 5");
     System.out.println (" ----------------------");
    String output ="";
   
    
    System.out.println ("kata yang belum diurutkan");
    for(char urutanhuruf : Kul){
        output=""+urutanhuruf;
        System.out.print(output);
    

    }
    

	}
}



//soal terakhir

<!doctype html>
<html>

	<head>
		<title> ini website saya soal terakhir</title>
	</head>
	<body>
	<center/>
	

	<form method="post" action="proses.php"> 
	
	<table border="1"> 
		<tr>
			<td> <input type="text" name="nama" required placeholder="tambah programer baru"/> </td>
			<td/>
			<td> <input type="submit" value="tambah"/>
		</td>
		</tr>
		<tr>
			<td> nama user </td>
			<td> <input type="text" name="nama" required placeholder="tambah skill"/> </td>
			<td> <input type="submit" value="tambah"/>
		</tr>
		<tr>
			<td> nama user 2</td>
			<td> <input type="text" name="nama" required placeholder="tambah skill"/> </td>
			<td> <input type="submit" value="tambah"/>
		</tr>
		<tr>
			<td> skill</td>
			<td> <input type="text" name="nama" required placeholder="tambah skill"/> </td>
			<td> <input type="submit" value="tambah"/>	
		</tr>
		
		<tr>
			<td> </td>
			<td> <input type="reset" value="reset"/> 
			<input type="submit" value="kirim data"/></td>
		</tr>
		

	</table>

	
	</form>
		
	
	</body>
	   
</html>





