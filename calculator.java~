import java.io.IOException;

class calculator{
  public static void main(String args[]){
    try{
	  int i = 0;
	  int intMax = 0;
	  String str = args[0];		//args[0]の文字をstrに代入
	  char c[] = new char[256];
	  for(int j = 0 ;j <= 255 ;j++)c[j] = '=';	//初期化(必要？)　//TODO:確認する
	  
	  while( (c[i] = str.charAt(i) ) != '='){
		System.out.println(c[i]);
		i++;
	  }
	  intMax = i;
	  for(i = 0 ;i <= intMax ;i++){
		switch (c[i]){
		  case '0';

		  default:
		    System.out.printin("対応していない文字が入力されたので終了します。\n対応している文字は0〜9と+です。");
	

		}
	  }
    }catch(Exception e){
      System.out.println(e);
    }
  }
}
