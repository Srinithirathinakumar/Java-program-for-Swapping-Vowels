# Java-program-for-Swapping-Vowels
Java program for Swapping Vowels
import java.util.*;
class Main{
    public static void main(String[] args) {
        Scanner sc=new Scanner(System.in);
        String s=sc.nextLine();
        char ch[]=s.toCharArray();
        for(int i=0, j=s.length()-1;i<=j;i++,j--){
            while(!(ch[i]=='a'||ch[i]=='e'||ch[i]=='i'||ch[i]=='o'||ch[i]=='u')){
            i++;
        }
        while(!(ch[j]=='a'||ch[j]=='e'||ch[j]=='i'||ch[j]=='o'||ch[j]=='u')){
            j--;
    }
    if(i<j){
        char c=ch[i];
        ch[i]=ch[j];
        ch[j]=c;
    }
}
for(int i=0;i<ch.length;i++){
    System.out.print(ch[i]);
}
}
}
