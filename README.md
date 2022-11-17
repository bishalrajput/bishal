public class overloding {
    String name;
    int roll;
    overloding(){
        name=null;
        roll=0;
    }
    overloding(String n,int r){
        name=n;
        roll=r;

    }
    void display(){
        System.out.println("name="+name+"roll="+roll);

    }
    public static void main(String []args){
        overloding o1=new overloding("subash",12);
        o1.display();
    }
}

