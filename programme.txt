/// \brief Bibliothèques utilisées dans ce projet

#include <stdio.h>
#include <stdint.h>
#include <iostream>
using namespace std;

/// \brief Fonction d'addition de deux nombres int32
///
///La fonction d'addition ci présente fait la somme des nombres en int32
/// \param A est un entier sur 32 bits
/// \param B est un entier sur 32 bits
/// \return Somme des paramètres
/// \sa add(int64_t A,int64_t B)
/// \sa add(float A,float B)
/// \sa add(double A,double B)

int32_t add( int32_t A , int32_t B)
{
    return A + B;
}

/// \brief Fonction de soustraction de deux nombres int32
///
///La fonction de soustraction ci présente fait la soustraction des nombres en int32
/// \param A est un entier sur 32 bits
/// \param B est un entier sur 32 bits
/// \return Soustraction des paramètres
/// \sa sou(int64_t A,int64_t B)
/// \sa sou(float A,float B)
/// \sa sou(double A,double B)

int32_t sou( int32_t A , int32_t B)
{
    return A - B;
}

/// \brief Fonction de multiplication de deux nombres int32
///
///La fonction de multiplication ci présente fait le produit des nombres en int32
/// \param A est un entier sur 32 bits
/// \param B est un entier sur 32 bits
/// \return Produit des paramètres
/// \sa mul(int64_t A,int64_t B)
/// \sa mul(float A,float B)
/// \sa mul(double A,double B)

int32_t mul( int32_t A , int32_t B)
{
    return A * B;
}

/// \brief Fonction de division de deux nombres int32
///
///La fonction de division ci présente fait le quotient des nombres en int32
/// \param A est un entier sur 32 bits
/// \param B est un entier sur 32 bits
/// \return Quotient des paramètres
/// \sa divi(int64_t A,int64_t B)
/// \sa divi(float A,float B)
/// \sa divi(double A,double B)

int32_t divi( int32_t A , int32_t B)
{
    return A / B;
}

/// \brief Fonction modulo de deux nombres int32
///
///La fonction modulo ci présente fait le reste du quotient des nombres en int32
/// \param A est un entier sur 32 bits
/// \param B est un entier sur 32 bits
/// \return Reste du quotient des paramètres
/// \sa mod(int64_t A,int64_t B)
/// \sa mod(float A,float B)
/// \sa mod(double A,double B)

int32_t mod( int32_t A , int32_t B)
{
    return A % B;
}

/// \brief Fonction d'addition  de deux nombres int64
///
///La fonction d'addition ci présente fait la somme des nombres en int64
/// \param A est un entier sur 64 bits
/// \param B est un entier sur 64 bits
/// \return Somme des paramètres
/// \sa add(int32_t A,int32_t B)
/// \sa add(float A,float B)
/// \sa add(double A,double B)

int64_t add( int64_t A , int64_t B)
{
    return A + B;
}

/// \brief Fonction de soustraction de deux nombres int64
///
///La fonction de soustraction ci présente fait la soustraction des nombres en int64
/// \param A est un entier sur 64 bits
/// \param B est un entier sur 64 bits
/// \return Soustraction des paramètres
/// \sa sou(int32_t A,int32_t B)
/// \sa sou(float A,float B)
/// \sa sou(double A,double B)

int64_t sou( int64_t A , int64_t B)
{
    return A - B;
}

/// \brief Fonction de multiplication de deux nombres int64
///
///La fonction de multiplication ci présente fait le produit des nombres en int64
/// \param A est un entier sur 64 bits
/// \param B est un entier sur 64 bits
/// \return Produit des paramètres
/// \sa mul(int32_t A,int32_t B)
/// \sa mul(float A,float B)
/// \sa mul(double A,double B)

int64_t mul( int64_t A , int64_t B)
{
    return A * B;
}

/// \brief Fonction de division de deux nombres int64
///
///La fonction de division ci présente fait le quotient des nombres en int64
/// \param A est un entier sur 64 bits
/// \param B est un entier sur 64 bits
/// \return Quotient des paramètres
/// \sa divi(int32_t A,int32_t B)
/// \sa divi(float A,float B)
/// \sa divi(double A,double B)

int64_t divi( int64_t A , int64_t B)
{
    return A / B;
}

/// \brief Fonction modulo de deux nombres int64
///
///La fonction modulo ci présente fait le reste du quotient en int64
/// \param A est un entier sur 64 bits
/// \param B est un entier sur 64 bits
/// \return Reste du quotient des paramètres
/// \sa mod(int32_t A,int32_t B)
/// \sa mod(float A,float B)
/// \sa mod(double A,double B)

int64_t mod( int64_t A , int64_t B)
{
    return A % B;
}

/// \brief Fonction d'addition  de deux nombres float
///
///La fonction d'addition ci présente fait la somme des nombres en float
/// \param A est un flottant sur 32 bits
/// \param B est un flottant sur 32 bits
/// \return Somme des paramètres
/// \sa add(int32_t A,int32_t B)
/// \sa add(int64_t A,int64_t B)
/// \sa add(double A,double B)

float add( float A , float B)
{
    return A + B;
}

/// \brief Fonction de soustraction de deux nombres float
///
///La fonction de soustraction ci présente fait la soustraction des nombres en float
/// \param A est un flottant sur 32 bits
/// \param B est un flottant sur 32 bits
/// \return Soustraction des paramètres
/// \sa sou(int32_t A,int32_t B)
/// \sa sou(int64_t A,int64_t B)
/// \sa sou(double A,double B)

float sou( float A , float B)
{
    return A - B;
}

/// \brief Fonction de multiplication de deux nombres float
///
///La fonction de multiplication ci présente fait le produit des nombres en float
/// \param A est un flottant sur 32 bits
/// \param B est un flottant sur 32 bits
/// \return Produit des paramètres
/// \sa mul(int32_t A,int32_t B)
/// \sa mul(int64_t A,int64_t B)
/// \sa mul(double A,double B)

float mul( float A , float B)
{
    return A * B;
}

/// \brief Fonction de division de deux nombres float
///
///La fonction de division ci présente fait le quotient des nombres en float
/// \param A est un flottant sur 32 bits
/// \param B est un flottant sur 32 bits
/// \return Quotient des paramètres
/// \sa divi(int32_t A,int32_t B)
/// \sa divi(int64_t A,int64_t B)
/// \sa divi(double A,double B)

float divi( float A , float B)
{
    return A / B;
}

/// \brief Fonction d'addition  de deux nombres double
///
///La fonction addition ci présente fait la somme de nombre en double
/// \param A est un flottant sur 64 bits
/// \param B est un flottant sur 64 bits
/// \return Somme des paramètres
/// \sa add(int32_t A,int32_t B)
/// \sa add(int64_t A,int64_t B)
/// \sa add(float A,float B)

double add( double A , double B)
{
    return A + B;
}

/// \brief Fonction de soustraction de deux nombres double
///
///La fonction addition ci présente fait la somme de nombre en double
/// \param A est un flottant sur 64 bits
/// \param B est un flottant sur 64 bits
/// \return Somme des paramètres
/// \sa sou(int32_t A,int32_t B)
/// \sa sou(int64_t A,int64_t B)
/// \sa sou(float A,float B)

double sou( double A , double B)
{
    return A - B;
}

/// \brief Fonction de multiplication de deux nombres double
///
///La fonction de multiplication ci présente fait le produit des nombres en double
/// \param A est un flottant sur 64 bits
/// \param B est un flottant sur 64 bits
/// \return Produit des paramètres
/// \sa mul(int32_t A,int32_t B)
/// \sa mul(int64_t A,int64_t B)
/// \sa mul(float A,float B)

double mul( double A , double B)
{
    return A * B;
}

/// \brief Fonction de division de deux nombres double
///
///La fonction de division ci présente fait le quotient des nombres en double
/// \param A est un flottant sur 64 bits
/// \param B est un flottant sur 64 bits
/// \return Quotient des paramètres
/// \sa divi(int32_t A,int32_t B)
/// \sa divi(int64_t A,int64_t B)
/// \sa divi(float A,float B)

double divi( double A , double B)
{
    return A / B;
}

int main()
{
    int choix;

    cout <<"\t\tCALCULATRICE\n\n\n"<< endl; 
    
	cout <<"Veuiller saisir le chiffre qui correspond a l'operation souhaitee\n"<< endl;
 
	cout <<"1 int32_t"<< endl;
	cout <<"2 int64_t"<< endl;
    cout <<"3 float"<< endl;
    cout <<"4 double"<< endl;

	cin >>choix;

	 switch (choix)
		{

		case 1:
			cout <<"INT32_T --- Veuiller saisir le chiffre qui correspond a l'operation souhaitee\n"<< endl;
			cout <<"1 Addition"<< endl;
			cout <<"2 Soustraction"<< endl;
			cout <<"3 Multiplication"<< endl;
			cout <<"4 Division"<< endl;
			cout <<"5 Modulo"<< endl;
 
			cin >>choix;
			int32_t a1, b1;

			switch (choix)
			{
			case 1:
				cout << "Entrer le premier opérateur : ";
				cin >> a1;
				cout << "Entrer le second opérateur : ";
				cin >> b1;
				cout <<"le resultat de l'addition "<<a1<<" + "<<b1<<" = "<<add(a1,b1)<<endl;
			break;

			case 2:
				cout << "Entrer le premier opérateur : ";
				cin >> a1;
				cout << "Entrer le second opérateur : ";
				cin >> b1;
				cout <<"le resultat de la soustraction "<<a1<<" - "<<b1<<" = "<<sou(a1,b1)<<endl;
			break;

			case 3: 
				cout << "Entrer le premier opérateur : ";
				cin >> a1;
				cout << "Entrer le second opérateur : ";
				cin >> b1;
				cout <<"le resultat de la multiplication "<<a1<<" * "<<b1<<" = "<<mul(a1,b1)<<endl;
			break;

			case 4:
				cout << "Entrer le premier opérateur : ";
				cin >> a1;
				cout << "Entrer le second opérateur : ";
				cin >> b1;
				cout <<"le resultat de la division "<<a1<<" / "<<b1<<" = "<<divi(a1,b1)<<endl;
			break;

			case 5:
				cout << "Entrer le premier opérateur : ";
				cin >> a1;
				cout << "Entrer le second opérateur : ";
				cin >> b1;
				cout <<"le resultat du modulo "<<a1<<" % "<<b1<<" = "<<mod(a1,b1)<<endl;
			break;
			}
		break;

		case 2:
			cout <<"INT64_T --- Veuiller saisir le chiffre qui correspond a l'operation souhaitee\n"<< endl;
			cout <<"1 Addition"<< endl;
			cout <<"2 Soustraction"<< endl;
			cout <<"3 Multiplication"<< endl;
			cout <<"4 Division"<< endl;
			cout <<"5 Modulo"<< endl;
 
			cin >>choix;
			int64_t a2, b2;

			switch (choix)
			{
			case 1:
				cout << "Entrer le premier opérateur : ";
				cin >> a2;
				cout << "Entrer le second opérateur : ";
				cin >> b2;
				cout <<"le resultat de l'addition "<<a2<<" + "<<b2<<" = "<<add(a2,b2)<<endl;
			break;

			case 2:
				cout << "Entrer le premier opérateur : ";
				cin >> a2;
				cout << "Entrer le second opérateur : ";
				cin >> b2;
				cout <<"le resultat de la soustraction "<<a2<<" - "<<b2<<" = "<<sou(a2,b2)<<endl;
			break;

			case 3: 
				cout << "Entrer le premier opérateur : ";
				cin >> a2;
				cout << "Entrer le second opérateur : ";
				cin >> b2;
				cout <<"le resultat de la multiplication "<<a2<<" * "<<b2<<" = "<<mul(a2,b2)<<endl;
			break;

			case 4:
				cout << "Entrer le premier opérateur : ";
				cin >> a2;
				cout << "Entrer le second opérateur : ";
				cin >> b2;
				cout <<"le resultat de la division "<<a2<<" / "<<b2<<" = "<<divi(a2,b2)<<endl;
			break;

			case 5:
				cout << "Entrer le premier opérateur : ";
				cin >> a2;
				cout << "Entrer le second opérateur : ";
				cin >> b2;
				cout <<"le resultat du modulo "<<a2<<" % "<<b2<<" = "<<mod(a2,b2)<<endl;
			break;
			}
		break;

		case 3:
			cout <<"FLOAT --- Veuiller saisir le chiffre qui correspond a l'operation souhaitee\n"<< endl;
			cout <<"1 Addition"<< endl;
			cout <<"2 Soustraction"<< endl;
			cout <<"3 Multiplication"<< endl;
			cout <<"4 Division"<< endl;
 
			cin >>choix;
			float a3, b3;

			switch (choix)
			{
			case 1:
				cout << "Entrer le premier opérateur : ";
				cin >> a3;
				cout << "Entrer le second opérateur : ";
				cin >> b3;
				cout <<"le resultat de l'addition "<<a3<<" + "<<b3<<" = "<<add(a3,b3)<<endl;
			break;

			case 2:
				cout << "Entrer le premier opérateur : ";
				cin >> a3;
				cout << "Entrer le second opérateur : ";
				cin >> b3;
				cout <<"le resultat de la soustraction "<<a3<<" - "<<b3<<" = "<<sou(a3,b3)<<endl;
			break;

			case 3: 
				cout << "Entrer le premier opérateur : ";
				cin >> a3;
				cout << "Entrer le second opérateur : ";
				cin >> b3;
				cout <<"le resultat de la multiplication "<<a3<<" * "<<b3<<" = "<<mul(a3,b3)<<endl;
			break;

			case 4:
				cout << "Entrer le premier opérateur : ";
				cin >> a3;
				cout << "Entrer le second opérateur : ";
				cin >> b3;
				cout <<"le resultat de la division "<<a3<<" / "<<b3<<" = "<<divi(a3,b3)<<endl;
			break;
			}
		break;

		case 4:
			cout <<"DOUBLE --- Veuiller saisir le chiffre qui correspond a l'operation souhaitee\n"<< endl;
			cout <<"1 Addition"<< endl;
			cout <<"2 Soustraction"<< endl;
			cout <<"3 Multiplication"<< endl;
			cout <<"4 Division"<< endl;
 
			cin >>choix;
			double a4, b4;

			switch (choix)
			{
			case 1:
				cout << "Entrer le premier opérateur : ";
				cin >> a4;
				cout << "Entrer le second opérateur : ";
				cin >> b4;
				cout <<"le resultat de l'addition "<<a4<<" + "<<b4<<" = "<<add(a4,b4)<<endl;
			break;

			case 2:
				cout << "Entrer le premier opérateur : ";
				cin >> a4;
				cout << "Entrer le second opérateur : ";
				cin >> b4;
				cout <<"le resultat de la soustraction "<<a4<<" - "<<b4<<" = "<<sou(a4,b4)<<endl;
			break;

			case 3: 
				cout << "Entrer le premier opérateur : ";
				cin >> a4;
				cout << "Entrer le second opérateur : ";
				cin >> b4;
				cout <<"le resultat de la multiplication "<<a4<<" * "<<b4<<" = "<<mul(a4,b4)<<endl;
			break;

			case 4:
				cout << "Entrer le premier opérateur : ";
				cin >> a4;
				cout << "Entrer le second opérateur : ";
				cin >> b4;
				cout <<"le resultat de la division "<<a4<<" / "<<b4<<" = "<<divi(a4,b4)<<endl;
			break;
			}
		break;
		}
    return 0;
}