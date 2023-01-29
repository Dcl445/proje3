# proje3
Scanner klv=new Scanner(System.in);
          System.out.println("Lutfen a kenarini giriniz");
          int a=klv.nextInt();
         System.out.println("Lutfen b kenarini giriniz");
          int b=klv.nextInt();
          System.out.println("Lutfen c kenarini giriniz");
          int c=klv.nextInt();
          double sonuc;
          double  cevre=(a+b+c)/2;
          double alan=cevre*(cevre-a)*(cevre-b)*(cevre-c);
          sonuc=Math.sqrt(alan);
          System.out.println("ALAN "+sonuc);
          


