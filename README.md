# Constructors-with-enumerations
enum Week{

 TUE(1), WED(1,2 ), MON;

    static {

        System.out.println("it is static block");

    }

    {

        System.out.println("it is an instance block");

    }

    Week( ){

        System.out.println("0 argument constructor");

    }

    Week(int a){

        System.out.println("1 argument constructor");

    }

    Week(int a, int b){

        System.out.println("2 argument constructor");

    }

    public static void main(String ... args){

        System.out.println("It is a main class");

    }

}

/*

it is an instance block

1 argument constructor

it is an instance block

2 argument constructor

it is an instance block

0 argument constructor

it is static block

It is a main class

 */
