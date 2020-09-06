int main(void)
{

    int h;
    int r;
    int s;
    int q;

    do
    {
        h = get_int("Height :");
    }
    while ((h < 0) || (h > 8));
    for (r = 1; r <= h; r++) 
    {
        for (s = (h - r); s > 0; s--)
        {
            printf(" "); 
        }
 
        for (q = 1; q <= (r + 0); q++)
        {   
            printf("#"); 
        }
 
        printf("\n");
    }
    return 0;
}
