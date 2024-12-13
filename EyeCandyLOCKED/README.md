This is where the password will be check and pass to checkIt function
bVar1 = checkIt(local_58);

The array our_array is filled with hexadecimal and decimal values that represent ASCII characters, after decode that we can get the password

bool checkIt(string *password)

{
  long lVar1;
  bool bVar2;
  char *pcVar3;
  long in_FS_OFFSET;
  string *password-local;
  char tmp;
  int i;
  int tmp_int;
  int our_array [15];
  
  lVar1 = *(long *)(in_FS_OFFSET + 0x28);
  our_array[0] = 100;
  our_array[1] = 0x30;
  our_array[2] = 0x30;
  our_array[3] = 0x72;
  our_array[4] = 0x31;
  our_array[5] = 0x24;
  our_array[6] = 0x6d;
  our_array[7] = 0x40;
  our_array[8] = 0x6c;
  our_array[9] = 0x69;
  our_array[10] = 99;
  our_array[11] = 0x69;
  our_array[12] = 0x6f;
  our_array[13] = 0x75;
  our_array[14] = 0x73;


