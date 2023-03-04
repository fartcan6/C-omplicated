# C-omplicated

**this is a simple C print code!** (_trust me_)

```C

#include <stdio.h>

int main(void) {
  int a, b, c, d, e, f, g, h, i, j, k, l, m, n, o, p, q, r, s, t, u, v, w, x, y, z;
  a = b = c = d = e = f = g = h = i = j = k = l = m = n = o = p = q = r = s = t = u = v = w = x = y = z = 0;
  int arr[26] = {a, b, c, d, e, f, g, h, i, j, k, l, m, n, o, p, q, r, s, t, u, v, w, x, y, z};
  char str[12] = "Hello World";
  for (int i = 0; i < 11; i++) {
    arr[str[i] - 97]++;
  }
  for (int i = 0; i < 26; i++) {
    switch(i) {
      case 7:
        printf("%c", arr[i] + 1);
        break;
      case 11:
        printf("%c", arr[i] - 19);
        break;
      case 14:
        printf("%c", arr[i] + 4);
        break;
      case 17:
        printf("%c", arr[i] - 20);
        break;
      case 22:
        printf("%c", arr[i] - 6);
        break;
      default:
        printf("%c", arr[i]);
        break;
    }
  }
  printf("!\n");
  return 0;
}

```
