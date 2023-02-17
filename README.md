String[] evenodd = {" number is even", " number is odd"};
for(int i = 0; i < 100; i++)
{
    int x = i;
    while (x > 1) x = x - 2;
    System.out.println(i + evenodd[x]);
}
