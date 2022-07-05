
  #include <stdio.h>
  #include <stdlib.h>
  #include <string.h>
  #include <ctype.h>
  #include <windows.h>
  #include <unistd.h>
  #include <conio.h>
  #include "conio.h"

  typedef int bool ;
  typedef char * string255 ;
  typedef char * string2 ;

  #define True 1
  #define False 0

  /** Implémentation **\: ARBRE BINAIRE DE STRUCTURES**/

  /** Structures statiques **/

  typedef struct Tssic Type_Tssic  ;
  typedef Type_Tssic * Typestr_Tssic ;
  typedef string255 Type1_Tssic  ;
  typedef string255 Type2_Tssic  ;
  typedef int Type3_Tssic  ;
  typedef string2 Type4_Tssic  ;
  struct Tssic
    {
      Type1_Tssic Champ1 ;
      Type2_Tssic Champ2 ;
      Type3_Tssic Champ3 ;
      Type4_Tssic Champ4 ;
    };

  Type1_Tssic Struct1_Tssic ( Typestr_Tssic S)
    {
      return  S->Champ1 ;
    }

  Type2_Tssic Struct2_Tssic ( Typestr_Tssic S)
    {
      return  S->Champ2 ;
    }

  Type3_Tssic Struct3_Tssic ( Typestr_Tssic S)
    {
      return  S->Champ3 ;
    }

  Type4_Tssic Struct4_Tssic ( Typestr_Tssic S)
    {
      return  S->Champ4 ;
    }

  void Aff_struct1_Tssic ( Typestr_Tssic S, Type1_Tssic Val )
    {
      strcpy( S->Champ1 , Val );
    }

  void Aff_struct2_Tssic ( Typestr_Tssic S, Type2_Tssic Val )
    {
      strcpy( S->Champ2 , Val );
    }

  void Aff_struct3_Tssic ( Typestr_Tssic S, Type3_Tssic Val )
    {
       S->Champ3 = Val ;
    }

  void Aff_struct4_Tssic ( Typestr_Tssic S, Type4_Tssic Val )
    {
      strcpy( S->Champ4 , Val );
    }


  /** Arbres de recherche binaire **/

  typedef Typestr_Tssic Typeelem_ATssic   ;
  typedef struct Noeud_ATssic * Pointeur_ATssic ;

  struct Noeud_ATssic
    {
      Typeelem_ATssic  Val ;
      Pointeur_ATssic Fg ;
      Pointeur_ATssic Fd ;
      Pointeur_ATssic Pere ;
     } ;

  Typeelem_ATssic Info_ATssic( Pointeur_ATssic P )
    { return P->Val;   }

  Pointeur_ATssic Fg_ATssic( Pointeur_ATssic P)
    { return P->Fg ; }

  Pointeur_ATssic Fd_ATssic( Pointeur_ATssic P)
    { return P->Fd ; }

  Pointeur_ATssic Pere_ATssic( Pointeur_ATssic P)
    { return P->Pere ; }

  void Aff_info_ATssic ( Pointeur_ATssic P, Typeelem_ATssic Val)
    {
      Typeelem_ATssic _Temp ;
      _Temp = malloc(sizeof(Type_Tssic));
      _Temp->Champ1 = malloc(255 * sizeof(char));
      _Temp->Champ2 = malloc(255 * sizeof(char));
      _Temp->Champ4 = malloc(2 * sizeof(char));
      /* Affectation globale de structure */
      strcpy(_Temp->Champ1, Val->Champ1);
      strcpy(_Temp->Champ2, Val->Champ2);
      _Temp->Champ3 = Val->Champ3;
      strcpy(_Temp->Champ4, Val->Champ4);
      Val = _Temp ;
       P->Val = Val ;
    }

  void Aff_fg_ATssic( Pointeur_ATssic P, Pointeur_ATssic Q)
    { P->Fg =  Q;  }

  void Aff_fd_ATssic( Pointeur_ATssic P, Pointeur_ATssic Q)
    { P->Fd =  Q ; }

  void Aff_pere_ATssic( Pointeur_ATssic P, Pointeur_ATssic Q)
    { P->Pere =  Q ; }

  void Creernoeud_ATssic( Pointeur_ATssic *P)
    {
      *P = (struct Noeud_ATssic *) malloc( sizeof( struct Noeud_ATssic))   ;
      (*P)->Val = malloc(sizeof(Type_Tssic));
      (*P)->Val->Champ1 = malloc( 255 * sizeof(char));
      (*P)->Val->Champ2 = malloc( 255 * sizeof(char));
      (*P)->Val->Champ4 = malloc( 2 * sizeof(char));
      (*P)->Fg = NULL;
      (*P)->Fd = NULL;
      (*P)->Pere = NULL;
    }

  void Liberernoeud_ATssic( Pointeur_ATssic P)
    { free( P ) ; }


  /** Implémentation **\: TABLEAU DE ARBRES BINAIRES DE STRUCTURES**/

  /** Tableaux **/

  typedef Pointeur_ATssic Typeelem_V100ATssic ;
  typedef Typeelem_V100ATssic * Typevect_V100ATssic ;

  Typeelem_V100ATssic Element_V100ATssic ( Typevect_V100ATssic V , int I1  )
    {
      return  *(V + I1-1 ) ;
    }

  void Aff_element_V100ATssic ( Typevect_V100ATssic V  , int I1 ,  Typeelem_V100ATssic Val )
    {
      *(V + I1-1 ) = Val ;
    }


  /** Implémentation **\: ARBRE BINAIRE DE STRUCTURES**/

  /** Structures statiques **/

  typedef struct Tiic Type_Tiic  ;
  typedef Type_Tiic * Typestr_Tiic ;
  typedef int Type1_Tiic  ;
  typedef int Type2_Tiic  ;
  typedef string2 Type3_Tiic  ;
  struct Tiic
    {
      Type1_Tiic Champ1 ;
      Type2_Tiic Champ2 ;
      Type3_Tiic Champ3 ;
    };

  Type1_Tiic Struct1_Tiic ( Typestr_Tiic S)
    {
      return  S->Champ1 ;
    }

  Type2_Tiic Struct2_Tiic ( Typestr_Tiic S)
    {
      return  S->Champ2 ;
    }

  Type3_Tiic Struct3_Tiic ( Typestr_Tiic S)
    {
      return  S->Champ3 ;
    }

  void Aff_struct1_Tiic ( Typestr_Tiic S, Type1_Tiic Val )
    {
       S->Champ1 = Val ;
    }

  void Aff_struct2_Tiic ( Typestr_Tiic S, Type2_Tiic Val )
    {
       S->Champ2 = Val ;
    }

  void Aff_struct3_Tiic ( Typestr_Tiic S, Type3_Tiic Val )
    {
      strcpy( S->Champ3 , Val );
    }


  /** Arbres de recherche binaire **/

  typedef Typestr_Tiic Typeelem_ATiic   ;
  typedef struct Noeud_ATiic * Pointeur_ATiic ;

  struct Noeud_ATiic
    {
      Typeelem_ATiic  Val ;
      Pointeur_ATiic Fg ;
      Pointeur_ATiic Fd ;
      Pointeur_ATiic Pere ;
     } ;

  Typeelem_ATiic Info_ATiic( Pointeur_ATiic P )
    { return P->Val;   }

  Pointeur_ATiic Fg_ATiic( Pointeur_ATiic P)
    { return P->Fg ; }

  Pointeur_ATiic Fd_ATiic( Pointeur_ATiic P)
    { return P->Fd ; }

  Pointeur_ATiic Pere_ATiic( Pointeur_ATiic P)
    { return P->Pere ; }

  void Aff_info_ATiic ( Pointeur_ATiic P, Typeelem_ATiic Val)
    {
      Typeelem_ATiic _Temp ;
      _Temp = malloc(sizeof(Type_Tiic));
      _Temp->Champ3 = malloc(2 * sizeof(char));
      /* Affectation globale de structure */
      _Temp->Champ1 = Val->Champ1;
      _Temp->Champ2 = Val->Champ2;
      strcpy(_Temp->Champ3, Val->Champ3);
      Val = _Temp ;
       P->Val = Val ;
    }

  void Aff_fg_ATiic( Pointeur_ATiic P, Pointeur_ATiic Q)
    { P->Fg =  Q;  }

  void Aff_fd_ATiic( Pointeur_ATiic P, Pointeur_ATiic Q)
    { P->Fd =  Q ; }

  void Aff_pere_ATiic( Pointeur_ATiic P, Pointeur_ATiic Q)
    { P->Pere =  Q ; }

  void Creernoeud_ATiic( Pointeur_ATiic *P)
    {
      *P = (struct Noeud_ATiic *) malloc( sizeof( struct Noeud_ATiic))   ;
      (*P)->Val = malloc(sizeof(Type_Tiic));
      (*P)->Val->Champ3 = malloc( 2 * sizeof(char));
      (*P)->Fg = NULL;
      (*P)->Fd = NULL;
      (*P)->Pere = NULL;
    }

  void Liberernoeud_ATiic( Pointeur_ATiic P)
    { free( P ) ; }


  /** Implémentation **\: FILE DE ARBRES BINAIRES DE STRUCTURES**/
  /** Files d'attente **/

  typedef Pointeur_ATssic Typeelem_FATssic ;
  typedef  struct Filedattente_FATssic * Pointeur_FATssic ;
  typedef  struct Maillon_FATssic * Ptliste_FATssic ;

  struct Maillon_FATssic
    {
      Typeelem_FATssic Val ;
      Ptliste_FATssic Suiv  ;
    };

  struct Filedattente_FATssic
    {
      Ptliste_FATssic Tete, Queue ;
    };

  void Creerfile_FATssic ( Pointeur_FATssic *Fil   )
    {
      *Fil = (struct Filedattente_FATssic *) malloc( sizeof( struct Filedattente_FATssic)) ;
      (*Fil)->Tete = NULL ;
      (*Fil)->Queue = NULL ;
    }

  bool Filevide_FATssic (Pointeur_FATssic Fil  )
    { return  Fil->Tete == NULL ;}

  void Enfiler_FATssic ( Pointeur_FATssic Fil , Typeelem_FATssic Val   )
    {
      Ptliste_FATssic Q;

      Q = (struct Maillon_FATssic *) malloc( sizeof( struct Maillon_FATssic))   ;
      Q->Val = Val ;
      Q->Suiv = NULL;
      if ( ! Filevide_FATssic(Fil) )
        Fil->Queue->Suiv = Q ;
      else Fil->Tete = Q;
        Fil->Queue = Q;
    }

  void Defiler_FATssic (Pointeur_FATssic Fil, Typeelem_FATssic *Val )
    {
      if (! Filevide_FATssic(Fil) )
        {
          *Val = Fil->Tete->Val ;
          Fil->Tete =  Fil->Tete->Suiv;
        }
      else printf ("%s \n", "File d'attente vide");
    }


  /** Implémentation **\: TABLEAU DE BOOLEENS**/

  /** Tableaux **/

  typedef bool Typeelem_V200b ;
  typedef Typeelem_V200b * Typevect_V200b ;

  Typeelem_V200b Element_V200b ( Typevect_V200b V , int I1  )
    {
      return  *(V + I1-1 ) ;
    }

  void Aff_element_V200b ( Typevect_V200b V  , int I1 ,  Typeelem_V200b Val )
    {
      *(V + I1-1 ) = Val ;
    }


  /** Variables du programme principal **/
  Pointeur_ATssic Ar;
  Typevect_V100ATssic T;
  Typevect_V100ATssic Pays;
  Pointeur_ATiic Arg;
  Pointeur_ATiic Arg1;
  Pointeur_ATiic Arg2;
  int I;
  int Nb_cas;
  int Nd;
  int Nr;
  int Age_max;
  int Age_min;
  int Total_occ;
  int Total;
  string2 Res;

  /** Fonctions standards **/

  int Aleanombre( int N )
    { return ( rand() % N ); }

  char  *Aleachaine ( int N )
    {
      int k;
      char  * Chaine = malloc(N+1);

      char Chr1[26] = "abcdefghijklmnopqrstuvwxyz";
      char Chr2[26] = "ABCDEFGHIJKLMNOPQRSTUVWXYZ";

      for (k=0;k<N; k++)
        switch ( rand() % 2 ){
        case 0 :  *(Chaine+k) = Chr1[rand() % 26] ; break ;
        case 1 :  *(Chaine+k) = Chr2[rand() % 26] ; break ;
        }
      Chaine[k] =  '\0' ;

      return (Chaine);
    }


  /** Initialisation d'une structure **/
  void Init_struct_Tssic ( Typestr_Tssic S, Type_Tssic S_ )
    {
      strcpy( S->Champ1 , S_.Champ1 );
      strcpy( S->Champ2 , S_.Champ2 );
      S->Champ3 = S_.Champ3 ;
      strcpy( S->Champ4 , S_.Champ4 );
    }


  /** Initialisation d'une structure **/
  void Init_struct_Tiic ( Typestr_Tiic S, Type_Tiic S_ )
    {
      S->Champ1 = S_.Champ1 ;
      S->Champ2 = S_.Champ2 ;
      strcpy( S->Champ3 , S_.Champ3 );
    }


  /** Prototypes des fonctions **/

  void Affich_arbre (Pointeur_ATssic *A , int *nb_lign , int *continuer);
  void Affich_arbre_glob (Pointeur_ATiic *A);
  void Creer_arbre (Pointeur_ATssic *A , int *Nd , int *Nr);
  void Creer_foret_glob (Typevect_V100ATssic *T , Pointeur_ATiic *Arg);
  void Creer_arbre_glob (Pointeur_ATssic *Ar , Pointeur_ATiic *Arg);
  int  Cas_compt (Pointeur_ATssic *Ar , int *Age , string2 *Res) ;
  void Insert_noeud (Pointeur_ATssic *Ar , Pointeur_ATssic *N);
  bool  Rech_cas_tab (Typevect_V200b *Tab , int *Age , string2 *Res) ;
  int  Statistique (Pointeur_ATiic *Arg , int *Bi , int *Bs , string2 *Res) ;
  int  Occurence_total (Pointeur_ATiic *Arg) ;

  /***********************************************************************
   ***********************************************************************/
void Affich_arbre (Pointeur_ATssic *A , int *nb_lign , int *continuer)
{
      /** Variables locales **/
      Pointeur_ATssic _Px1;
      Type_Tssic _Struct_Temp1;
      Pointeur_ATssic _Px2;

      /** Corps du module **/
      if ( *continuer == 1)
      {
        if( *A != NULL)
        {
            _Px1 =  Fg_ATssic ( *A ) ;
            Affich_arbre ( &_Px1 , nb_lign , continuer) ;
            if (*continuer == 1)
            {
                if (*nb_lign==20)
                {
                    printf("\nVoulez-vous continuer(1)/arreter(0)...");
                    scanf("%d",continuer);
                }
                if ((*nb_lign<20) || (*continuer == 1))
                {
                    /** Ecriture d'une structure */
                    _Struct_Temp1 = *Info_ATssic(*A);
                    printf ( "\n Nom: %s", _Struct_Temp1.Champ1 );
                    printf ( "\n Prenom: %s", _Struct_Temp1.Champ2 );
                    printf ( "\n Age: %d", _Struct_Temp1.Champ3 );
                    printf ( "\n Resultat: %s", _Struct_Temp1.Champ4 ) ;
                    printf("\n============");
                    *nb_lign=((*nb_lign)+1) % 21;
                    _Px2 =  Fd_ATssic ( *A ) ;
                    Affich_arbre ( &_Px2 , nb_lign , continuer ) ;
                }
            } ;

        }
    }
}
  /************************************************************************
   ************************************************************************/
  void Affich_arbre_glob (Pointeur_ATiic *A)
    {
      /** Variables locales **/
      Pointeur_ATiic _Px1;
      Type_Tiic _Struct_Temp2;
      Pointeur_ATiic _Px2;

      /** Corps du module **/
     if( *A != NULL) {
       _Px1 =  Fg_ATiic ( *A ) ;
       Affich_arbre_glob ( &_Px1) ;
       /** Ecriture d'une structure */
       _Struct_Temp2 = *Info_ATiic(*A);
       printf ( "\nAge: %d", _Struct_Temp2.Champ1 );
       printf ( "\nOccurences: %d", _Struct_Temp2.Champ2 );
       printf ( "\nResultat: %s", _Struct_Temp2.Champ3 ) ;
       printf ( "\n============");
       _Px2 =  Fd_ATiic ( *A ) ;
       Affich_arbre_glob ( &_Px2) ;

     } ;

    }
  /**************************************************************************
   **************************************************************************/
  void Creer_arbre (Pointeur_ATssic *A , int *Nd , int *Nr)
    {
      /** Variables locales **/
      Pointeur_ATssic N;
      Typestr_Tssic S;
      int J;
      int I;
      Type_Tssic S_S;

      /** Corps du module **/
     S = malloc(sizeof(Type_Tssic));
     S->Champ1 = malloc(255 * sizeof(char));
     S->Champ2 = malloc(255 * sizeof(char));
     S->Champ4 = malloc(2 * sizeof(char));
     *A  =  NULL ;
     for( J  =  1 ;J <=  *Nd + *Nr   ; ++J){
       I  =  Aleanombre(2 ) ;
       if( ( *Nd != 0 ) && ( *Nr != 0 )) {
         if( I == 0) {
           S_S.Champ1= malloc(255 * sizeof(char));
           strcpy(S_S.Champ1 , Aleachaine(10)) ;
           S_S.Champ2= malloc(255 * sizeof(char));
           strcpy(S_S.Champ2 , Aleachaine(10)) ;
           S_S.Champ3 = Aleanombre(100) ;
           S_S.Champ4= malloc(2 * sizeof(char));
           strcpy(S_S.Champ4 , "D") ;
           Init_struct_Tssic ( S , S_S )  ;
           *Nd  =  *Nd - 1 ;
           }
         else
           {
           S_S.Champ1= malloc(255 * sizeof(char));
           strcpy(S_S.Champ1 , Aleachaine(10)) ;
           S_S.Champ2= malloc(255 * sizeof(char));
           strcpy(S_S.Champ2 , Aleachaine(10)) ;
           S_S.Champ3 = Aleanombre(100) ;
           S_S.Champ4= malloc(2 * sizeof(char));
           strcpy(S_S.Champ4 , "R") ;
           Init_struct_Tssic ( S , S_S )  ;
           *Nr  =  *Nr - 1 ;

         } ;
         }
       else
         {
         if( *Nr == 0) {
           S_S.Champ1= malloc(255 * sizeof(char));
           strcpy(S_S.Champ1 , Aleachaine(10)) ;
           S_S.Champ2= malloc(255 * sizeof(char));
           strcpy(S_S.Champ2 , Aleachaine(10)) ;
           S_S.Champ3 = Aleanombre(100) ;
           S_S.Champ4= malloc(2 * sizeof(char));
           strcpy(S_S.Champ4 , "D") ;
           Init_struct_Tssic ( S , S_S )  ;
           }
         else
           {
           S_S.Champ1= malloc(255 * sizeof(char));
           strcpy(S_S.Champ1 , Aleachaine(10)) ;
           S_S.Champ2= malloc(255 * sizeof(char));
           strcpy(S_S.Champ2 , Aleachaine(10)) ;
           S_S.Champ3 = Aleanombre(100) ;
           S_S.Champ4= malloc(2 * sizeof(char));
           strcpy(S_S.Champ4 , "R") ;
           Init_struct_Tssic ( S , S_S )  ;

         }
       } ;
       Creernoeud_ATssic (& N ) ;
       Aff_info_ATssic ( N , S ) ;
       Aff_fg_ATssic ( N , NULL ) ;
       Aff_fd_ATssic ( N , NULL ) ;
       Insert_noeud ( & *A , & N ) ;

     }
    }
  /***************************************************************************
   *****************************************************************************/
  void Creer_foret_glob (Typevect_V100ATssic *T , Pointeur_ATiic *Arg)
    {
      /** Variables locales **/
      Pointeur_ATssic Ar;
      int I;

      /** Corps du module **/
     *Arg  =  NULL ;
     for( I  =  1 ;I <=  100   ; ++I){
       Ar  =  Element_V100ATssic ( *T , I   ) ;
       Creer_arbre_glob ( & Ar , & *Arg ) ;

     }
    }
  /****************************************************************************
   ****************************************************************************/
  void Creer_arbre_glob (Pointeur_ATssic *Ar , Pointeur_ATiic *Arg)
    {
      /** Variables locales **/
      Pointeur_ATiic Ng;
      Pointeur_ATiic P;
      Pointeur_FATssic F;
      Pointeur_ATssic N;
      Typestr_Tiic S;
      Typevect_V200b Tab;
      int Age;
      int Cpt1;
      int Cpt2;
      int I;
      string2 Res;
      bool Trouv;
      bool Trouvg;
      bool Trouvd;
      Type_Tiic S_S;

      /** Corps du module **/
     S = malloc(sizeof(Type_Tiic));
     S->Champ3 = malloc(2 * sizeof(char));
     Tab = malloc(200 * sizeof(int));
     Res = malloc(2 * sizeof(char));
     for( I  =  1 ;I <=  200   ; ++I){
       Aff_element_V200b ( Tab , I   , False ) ;

     } ;
     Creerfile_FATssic (& F ) ;
     if( *Ar != NULL) {
       Enfiler_FATssic ( F , *Ar ) ;

     } ;
     while( ( ! Filevide_FATssic ( F ) )) {
       Defiler_FATssic ( F , &N ) ;
       Age  =  Struct3_Tssic ( Info_ATssic ( N )  ) ;
       strcpy (Res,   Struct4_Tssic ( Info_ATssic ( N )  )) ;
       if( ! Rech_cas_tab ( & Tab , & Age , & Res )) {
         Trouv  =  False ;
         Trouvg  =  False ;
         Trouvd  =  False ;
         P  =  *Arg ;
         while( ( P != NULL ) && ( ! Trouv ) && ( ! Trouvg ) && ( ! Trouvd )) {
           if( ( ( Struct1_Tiic ( Info_ATiic ( P )  ) == Age ) && (strcmp( Struct3_Tiic ( Info_ATiic ( P )  ), Res) == 0  ) )) {
             Trouv  =  True ;
             }
           else
             {
             if( ( Struct1_Tiic ( Info_ATiic ( P )  ) < Age ) || ( ( Struct1_Tiic ( Info_ATiic ( P )  ) == Age ) && (strcmp( Struct3_Tiic ( Info_ATiic ( P )  ), "D") == 0  ) )) {
               if( ( Fd_ATiic ( P ) != NULL )) {
                 P  =  Fd_ATiic ( P ) ;
                 }
               else
                 {
                 Trouvd  =  True ;

               } }
             else
               {
               if( ( Fg_ATiic ( P ) != NULL )) {
                 P  =  Fg_ATiic ( P ) ;
                 }
               else
                 {
                 Trouvg  =  True ;

               }
             }
           }
         } ;
         Cpt1  =  Cas_compt ( & N , & Age , & Res ) ;
         if( Trouv) {
           Cpt2  =  Struct2_Tiic ( Info_ATiic ( P )  ) + Cpt1 ;
           S_S.Champ1 = Age ;
           S_S.Champ2 = Cpt2 ;
           S_S.Champ3= malloc(2 * sizeof(char));
           strcpy(S_S.Champ3 , Res) ;
           Init_struct_Tiic ( S , S_S )  ;
           Aff_info_ATiic ( P , S ) ;
           }
         else
           {
           S_S.Champ1 = Age ;
           S_S.Champ2 = Cpt1 ;
           S_S.Champ3= malloc(2 * sizeof(char));
           strcpy(S_S.Champ3 , Res) ;
           Init_struct_Tiic ( S , S_S )  ;
           Creernoeud_ATiic (& Ng ) ;
           Aff_info_ATiic ( Ng , S ) ;
           Aff_fg_ATiic ( Ng , NULL ) ;
           Aff_fd_ATiic ( Ng , NULL ) ;
           if( P == NULL) {
             *Arg  =  Ng ;
             }
           else
             {
             if( Trouvg) {
               Aff_fg_ATiic ( P , Ng ) ;
               }
             else
               {
               Aff_fd_ATiic ( P , Ng ) ;

             }
           }
         } ;
         if(strcmp( Res, "D") == 0 ) {
           Aff_element_V200b ( Tab , 2 * Age + 1   , True ) ;
           }
         else
           {
           Aff_element_V200b ( Tab , 2 * Age + 2   , True ) ;

         }
       } ;
       if( Fg_ATssic ( N ) != NULL) {
         Enfiler_FATssic ( F , Fg_ATssic ( N ) ) ;

       } ;
       if( Fd_ATssic ( N ) != NULL) {
         Enfiler_FATssic ( F , Fd_ATssic ( N ) ) ;

       } ;

     } ;

    }
  /****************************************************************************
  *****************************************************************************/
  int  Cas_compt (Pointeur_ATssic *Ar , int *Age , string2 *Res)
    {
      /** Variables locales **/
      int  Cas_compt2 ;
      int Cpt;
      Pointeur_ATssic _Px1;
      Pointeur_ATssic _Px2;

      /** Corps du module **/
     Cpt  =  0 ;
     if( *Ar != NULL) {
       if( ( Struct3_Tssic ( Info_ATssic ( *Ar )  ) == *Age ) && (strcmp( Struct4_Tssic ( Info_ATssic ( *Ar )  ), *Res) == 0  )) {
         Cpt  =  1 ;

       } ;
       if( ( Struct3_Tssic ( Info_ATssic ( *Ar )  ) < *Age ) || ( ( Struct3_Tssic ( Info_ATssic ( *Ar )  ) == *Age ) && (strcmp( Struct4_Tssic ( Info_ATssic ( *Ar )  ), "D") == 0  ) )) {
         _Px1 =  Fd_ATssic ( *Ar ) ;
         Cpt  =  Cpt + Cas_compt ( &_Px1, & *Age , & *Res ) ;
         }
       else
         {
         _Px2 =  Fg_ATssic ( *Ar ) ;
         Cpt  =  Cpt + Cas_compt ( &_Px2, & *Age , & *Res ) ;

       }
     } ;
     Cas_compt2  =  Cpt ;

     return Cas_compt2 ;
    }
  /*****************************************************************************
   *****************************************************************************/
  void Insert_noeud (Pointeur_ATssic *Ar , Pointeur_ATssic *N)
    {
      /** Variables locales **/
      Pointeur_ATssic P;
      bool Trouv;

      /** Corps du module **/
     Trouv  =  False ;
     P  =  *Ar ;
     while( ( ! Trouv )) {
       if( P == NULL) {
         Trouv  =  True ;
         }
       else
         {
         if( ( Struct3_Tssic ( Info_ATssic ( P )  ) > Struct3_Tssic ( Info_ATssic ( *N )  ) ) || ( ( Struct3_Tssic ( Info_ATssic ( P )  ) == Struct3_Tssic ( Info_ATssic ( *N )  ) ) && (strcmp( Struct4_Tssic ( Info_ATssic ( P )  ), "R") == 0  ) )) {
           if( Fg_ATssic ( P ) == NULL) {
             Trouv  =  True ;
             }
           else
             {
             P  =  Fg_ATssic ( P ) ;

           } ;
           }
         else
           {
           if( Fd_ATssic ( P ) == NULL) {
             Trouv  =  True ;
             }
           else
             {
             P  =  Fd_ATssic ( P ) ;

           } ;

         } ;

       } ;

     } ;
     if( P == NULL) {
       *Ar  =  *N ;
       }
     else
       {
       if( ( Struct3_Tssic ( Info_ATssic ( P )  ) > Struct3_Tssic ( Info_ATssic ( *N )  ) ) || ( ( Struct3_Tssic ( Info_ATssic ( P )  ) == Struct3_Tssic ( Info_ATssic ( *N )  ) ) && (strcmp( Struct4_Tssic ( Info_ATssic ( P )  ), "R") == 0  ) )) {
         Aff_fg_ATssic ( P , *N ) ;
         }
       else
         {
         Aff_fd_ATssic ( P , *N ) ;

       }
     }
    }
  /******************************************************************************
   ******************************************************************************/
  bool  Rech_cas_tab (Typevect_V200b *Tab , int *Age , string2 *Res)
    {
      /** Variables locales **/
      bool  Rech_cas_tab2 ;
      bool Trouv;

      /** Corps du module **/
     if(strcmp( *Res, "D") == 0 ) {
       Trouv  =  Element_V200b ( *Tab , 2 * *Age + 1   ) ;
       }
     else
       {
       Trouv  =  Element_V200b ( *Tab , 2 * *Age + 2   ) ;

     } ;
     Rech_cas_tab2  =  Trouv ;

     return Rech_cas_tab2 ;
    }
  /***************************************************************************
   *****************************************************************************/
  int  Statistique (Pointeur_ATiic *Arg , int *Bi , int *Bs , string2 *Res)
    {
      /** Variables locales **/
      int  Statistique2 ;
      int Cpt;
      Pointeur_ATiic _Px1;
      Pointeur_ATiic _Px2;

      /** Corps du module **/
     Cpt  =  0 ;
     if( *Arg != NULL) {
       if( ( ( Struct1_Tiic ( Info_ATiic ( *Arg )  ) >= *Bi ) && ( Struct1_Tiic ( Info_ATiic ( *Arg )  ) <= *Bs ) && (strcmp( Struct3_Tiic ( Info_ATiic ( *Arg )  ), *Res) == 0  ) )) {
         Cpt  =  Struct2_Tiic ( Info_ATiic ( *Arg )  ) ;

       } ;
       if( Struct1_Tiic ( Info_ATiic ( *Arg )  ) >= *Bi) {
         _Px1 =  Fg_ATiic ( *Arg ) ;
         Cpt  =  Cpt + Statistique ( &_Px1, & *Bi , & *Bs , & *Res ) ;

       } ;
       if( Struct1_Tiic ( Info_ATiic ( *Arg )  ) <= *Bs) {
         _Px2 =  Fd_ATiic ( *Arg ) ;
         Cpt  =  Cpt + Statistique ( &_Px2, & *Bi , & *Bs , & *Res ) ;

       } ;

     } ;
     Statistique2  =  Cpt ;

     return Statistique2 ;
    }
  /****************************************************************************
   ****************************************************************************/
  int  Occurence_total (Pointeur_ATiic *Arg)
    {
      /** Variables locales **/
      int  Occurence_total2 ;
      int Cpt;
      Pointeur_ATiic _Px1;
      Pointeur_ATiic _Px2;

      /** Corps du module **/
     Cpt  =  0 ;
     if( *Arg != NULL) {
       Cpt  =  Struct2_Tiic ( Info_ATiic ( *Arg )  ) ;
       _Px1 =  Fg_ATiic ( *Arg ) ;
       Cpt  =  Cpt + Occurence_total ( &_Px1) ;
       _Px2 =  Fd_ATiic ( *Arg ) ;
       Cpt  =  Cpt + Occurence_total ( &_Px2) ;

     } ;
     Occurence_total2  =  Cpt ;

     return Occurence_total2 ;
    }
/********************************************************
*********************************************************/
static int __FOREGROUND = 0;
void textcolor (int color)
{
    __FOREGROUND = color;
    SetConsoleTextAttribute (GetStdHandle (STD_OUTPUT_HANDLE), color);
}
/********************************************************
*********************************************************/
typedef struct
{
    char nom_pay[50];
    int ND;
    int NR;
}pay;
void lect_nbcas(pay* reel)
{
    FILE *fptr=fopen("corona.txt","r");
    char c;
    int i=0,j;
    while(!feof(fptr))
    {
        c=fgetc(fptr);
        j=0;
        c=fgetc(fptr);
        while (c!='"')
        {
            reel[i].nom_pay[j]=c;
            j++;
            c=fgetc(fptr);
        }
        reel[i].nom_pay[j]='\0';
        fscanf(fptr,"%d",&reel[i].ND);
        fscanf(fptr,"%d",&reel[i].NR);
        i++;
        c=fgetc(fptr);
    }
}
/********************************************************
*********************************************************/
int rech_pay(pay *reel , char *nom_pay)
{
    int i=0;
    while ((i<100) && (strcmp(reel[i].nom_pay,nom_pay)))
    {
        i++;
    }
    return i;
}

/********************************************************
*********************************************************/
void affich_DR_pay(pay *reel)
{
    printf("\nVoulez-vous afficher les statistiques:");
    printf("\n1-D'un pays.");
    printf("\n2-De tous les pays.");
    printf("\nEntrer le numero de votre choix: ");

    int choix,i;
    char nom_pay[50];

    scanf("%d",&choix);
    switch (choix)
    {
        case 1 :
            printf("\nDonner le nom du pays:\t");
            getchar();
            fgets(nom_pay,50,stdin);
            nom_pay[strlen(nom_pay)-1]='\0';
            i=rech_pay(reel,nom_pay);
            if (i!=100)
            {
                textcolor(3);
                printf("%s\t",reel[i].nom_pay);
                textcolor(4);
                printf("ND: ");
                textcolor(15);
                printf("%d\t",reel[i].ND);
                textcolor(2);
                printf("NR: ");
                textcolor(15);
                printf("%d\n",reel[i].NR);
            }
            else
            {
                textcolor(4);
                printf("\nPays non trouve!");
                textcolor(15);
            }
            break;
        case 2 :
            for (i=0;i<100;i++)
            {
                textcolor(3);
                printf("%s ",reel[i].nom_pay);
                textcolor(15);
                printf("%d\t",reel[i].ND);
                printf("%d\n",reel[i].NR);
            }
            break;
        default :
            textcolor(4);
            printf("\nChoix invalid!");
            textcolor(15);
    }
}
/*******************************************************
********************************************************/
int minimum(int a, int b)
{
    if (b<a) return b;
    return a;
}
/*******************************************************
********************************************************/
int requette_glob(Pointeur_ATiic Arg , int Age_min , int Age_max ,string2 Res)
{
     int Total,Total_occ;

        Total  =  Occurence_total ( & Arg ) ;
        Total_occ  =  Statistique ( & Arg , & Age_min , & Age_max , & Res ) ;
        return (Total_occ*100)/Total;
}
/*******************************************************
********************************************************/
  int main(int argc, char *argv[])
{
     T = malloc(100 * sizeof(Pointeur_ATssic));
     int _Izw2;for (_Izw2=0; _Izw2<100; ++_Izw2)
       T[_Izw2] = malloc( sizeof(Pointeur_ATssic ));
     Pays = malloc(100 * sizeof(Pointeur_ATssic));
     int _Izw3;for (_Izw3=0; _Izw3<100; ++_Izw3)
       Pays[_Izw3] = malloc( sizeof(Pointeur_ATssic ));
     Res = malloc(2 * sizeof(char));

     pay reel[100];

     for( I  =  1 ;I <=  100   ; ++I){
       Nb_cas  =  Aleanombre(21 ) ;
       Nd  =  Aleanombre ( Nb_cas + 1 ) ;
       Nr  =  Nb_cas - Nd ;
       Creer_arbre ( & Ar , & Nd , & Nr ) ;
       Aff_element_V100ATssic ( T , I   , Ar ) ;

     } ;
     lect_nbcas(reel);

     int md;
     int mr;

     for ( I = 1 ; I <= 100 ; ++I)
     {
       Nd = reel[I-1].ND  ;
       Nr = reel[I-1].NR  ;
       md=minimum(Nd,1000);
       mr=minimum(Nr,1000);
       Creer_arbre ( & Ar , & md , & mr ) ;
       Aff_element_V100ATssic ( Pays , I   , Ar ) ;
     }
     Creer_foret_glob ( & T , & Arg ) ;
     Creer_foret_glob ( & Pays , & Arg1 ) ;
    textcolor(14);
    printf("***********************************************************************************************************************\n");
    printf("                                            Concue et Realise par:                                                     \n");
    printf("                                               BOUKETTA Ammar                                                 \n");
    printf("                              -ESI:Ecole Nationale Superieur d'Informatique EX:INI-ESI                                 \n");
    printf("                                               Promotion:2019                                                \n");
    printf("***********************************************************************************************************************\n");
    textcolor(15);
    char rep;
     do
     {
        int choix;
        printf ("\n============================================" ) ;
        printf ("\nChoisir une des option suivantes: ");
        printf ("\n1-Afficher ND et NR selon le pays.");
        printf ("\n2-Afficher la liste des cas dans un pay.");
        printf ("\n3-Afficher les statistiques globales.");
        printf ("\n4-Afficher les statistiques globales sur un pays.");
        printf ("\n5-Lancer une requete globale.");
        printf ("\n6-Lancer une requete sur un pay.");
        printf ("\n7-Sortir de l'application.");
        printf ( "\n============================================\n" );
        char nom_pay[50];
        int nb_lign=0 , continuer=1,sortir=0;
        printf ("\nEntrer le numero de votre choix: ");
        scanf("%d",&choix);
        switch (choix)
        {
            case 1 :
                affich_DR_pay(reel);
            break;
            case 2 :
                printf("\nDonner le nom du pays: ");
                getchar();
                fgets(nom_pay,50,stdin);
                nom_pay[strlen(nom_pay)-1]='\0';
                I=rech_pay(reel , nom_pay);
                if (I!=100) Affich_arbre( & Pays[I] , &nb_lign , &continuer);
                else
                {
                    textcolor(4);
                    printf("\nPays non trouve!");
                    textcolor(15);
                }
            break;
            case 3 :
                Total=Occurence_total(& Arg );
                printf("\nLe nombre total des cas fermees: %d",Total);
                printf("\nLe nombre total des morts: %d",(Total*requette_glob( Arg1 , 0 , 100 , "D"))/100);
                printf("\nLe nombre total des recuperations: %d",(Total*requette_glob( Arg1 , 0 , 100 , "R"))/100);
                Affich_arbre_glob(& Arg );
            break;
            case 4 :
                Arg2=NULL;
                printf("Entrer le nom du pay: ");
                scanf("%s",nom_pay);
                I=rech_pay(reel,nom_pay);
                if (I!=100)
                {
                    Creer_arbre_glob( & Pays[I] , & Arg2 );
                    Total=Occurence_total(& Arg2 );
                    printf("\nLe nombre total des cas fermees: %d",Total);
                    printf("\nLe nombre total des morts: %d",(Total*requette_glob( Arg1 , 0 , 100 , "D"))/100);
                    printf("\nLe nombre total des recuperations: %d",(Total*requette_glob( Arg1 , 0 , 100 , "R"))/100);
                    Affich_arbre_glob(& Arg2 );
                }
            break;
            case 5 :
                printf ("\nLancer une requete par: ");
                printf ("\n1-L'interval de l'age.");
                printf ("\n2-Seperieur a l'age...");
                printf ("\n3-Inferieur a l'age...\n");
                scanf  ("%d",&choix);
                if((choix==1) || (choix==2))
                {
                    printf ( "\nAge minimum : " ) ;
                    scanf ( " %d", &Age_min ) ;
                }
                else Age_min=0;
                if ((choix==1) || (choix==3))
                {
                printf ( "Age maximum : " ) ;
                scanf ( " %d", &Age_max ) ;
                }
                else Age_max=100;
                printf ( "La resultat (D/R) : " ) ;
                scanf ( " %s", Res ) ;
                printf ( "le percentage de cette cas est: %d",requette_glob( Arg1 , Age_min , Age_max , Res));
                printf ( "%%" ) ;
            break;
            case 6 :
                printf ("\nLancer une requete par: ");
                printf ("\n1-L'interval de l'age.");
                printf ("\n2-Seperieur a l'age...");
                printf ("\n3-Inferieur a l'age...\n");
                scanf  ("%d",&choix);
                if((choix==1) || (choix==2))
                {
                    printf ( "\nAge minimum : " ) ;
                    scanf ( " %d", &Age_min ) ;
                }
                else Age_min=0;
                if ((choix==1) || (choix==3))
                {
                printf ( "Age maximum : " ) ;
                scanf ( " %d", &Age_max ) ;
                }
                else Age_max=100;
                printf ( "La resultat (D/R) : " ) ;
                scanf ( " %s", Res ) ;
                Arg2=NULL;
                printf("Entrer le nom du pay: ");
                scanf("%s",nom_pay);
                I=rech_pay(reel,nom_pay);
                if (I!=100)
                {
                    Creer_arbre_glob( & Pays[I] , & Arg2 );
                    printf ( "le percentage de cette cas est: %d",requette_glob( Arg2 , Age_min , Age_max , Res));
                    printf ( "%%" ) ;
                }
                else
                {
                    textcolor(4);
                    printf("\nPays non trouve!");
                    textcolor(15);
                }
            break;
            case 7 :
                sortir=1;
            break;
            default :
                textcolor(4) ;
                printf("\nChoix invalid!");
                textcolor(15) ;
        }
        if (sortir==0)
        {
            printf("\nVoulez-vous continuer (o/n)?...");
            do{
                scanf("%c",&rep);
            }while(rep=='\n');
        }
        else rep='n';
     } while (tolower(rep)=='o');
    printf("\n");
    textcolor(14);
    printf("\nPour signaler les bugs et les erreurs:\n");
    printf("\tja_bouketta@esi.dz\n");
    printf("\n© 2020 Toutes les droits reservees.\n");
    textcolor(15);
    system("PAUSE");
    return 0;
}
