Groupe 9: Gérard Ngindu , Arouna FAKOUE MFOUAPON ,Winsley SAHA , Sebastien ERVE , Omar KALLEL

Avant de lancer le programme vous devez importer dans Mongodb le json Restaurant qui vient avec.
Il doit être importer dans la db "DbRestaurant" et la collection "ListeRestaurant" pour fonctionner.

Si il y a une erreur du style : 'ttk' is not defined il faut installer le package tkinter (normalement il est
inclus dans toute les versions de python 3.X)

Si cela persiste remplacer :
import tkinter
import tkinter.ttk

Par:
try:
    from tkinter import *
    from tkinter import ttk
except ImportError:
    from Tkinter import *
    from Tkinter import ttk
