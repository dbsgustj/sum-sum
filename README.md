# sum-sum
Scanner sc = new Scanner(System.in);
		int sum=0;
		System.out.println("몇부터");
		int a = sc.nextInt();
		System.out.println("몇까지 더할까요?");
		int b = sc.nextInt();
		for(int i = a;i<= b ; i++) {
			sum +=i;
		}
		System.out.println(+a+"부터 "+b+"까지 더하면 "+sum+"입니다");
	}

}
