# incluir <bits/stdc++.h>
practica para hacer el repositorio
double simplex(vector<vector>& tabla, int m, int n) {int columna = 0; 
for (int =1; j<n;j++) {if (tabl[m-1][j] <tabl[m-1][columna}) {columna = j;
 }
  }
  if (tabl[m-1][columna] >= 0) ( //sacar valor opt return O; 
}
int fila = -1; for(int i=0;1<m-1,1++) {if (tabl[i][columna] > 0 && (fila
==-1 //tabl[i][n-1]/tablal[i] [columna] < tabl[fila][n-1]/tabla[fila[i]columna])) {fila = i;}} if (fila ==-1) }//no encont ningun fila valida return 0;}
doble pivote = tabl[fila][columna]; for (int j = 0;) j< n; j++) {tabl[fila][j] /= pivote;}  for (int ¡ = 0;i<m; i++) {if i!= fila) { double ElementoPivote = tabl[i][columna]; for (int j=0; j<n; j++) {
tabl[i][j] -= ElementoPivote * tabla[fila][j]; }}} return
simplex(tabl, m, n);}

int main(){cin.tie(nullptr); ios_base::sync_with_stdio(falso);
int n, m; 
string restricciones;
cin >> n >> 4;

vector<vector<double>> tabl(m+1, vector<doub

for (int i = 0; i <m; i++) {
for (int j= 0; j <n; j++) {
cin >> tabl[i][j];
}
cin >> restricciones;
cin >> tabl[i][n+m];;
tabla[i][n+i] = 1; //variable 
If (restricciones l= "<=" && ((tabla[i](n+
for (Ant j= 0; J <N; j++{L
tabla[i][J] *= -1;
 }
}
tabl[m][n+m] =1; variable holgura
}
