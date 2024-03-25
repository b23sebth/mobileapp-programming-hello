
# Rapport

Jag började med att ändra "app_name" i strings.xml till "Lasagne".
```
<resources>
    <string name="app_name">Lasagne</string>
</resources>
```
Sedan ändrade jag Android:text inuti <TextView> till "Lasagne är nice".
```
<TextView
    android:layout_width="wrap_content"
    android:layout_height="wrap_content"
    android:text="Lasagne är nice!"
    app:layout_constraintBottom_toBottomOf="parent"
    app:layout_constraintEnd_toEndOf="parent"
    app:layout_constraintStart_toStartOf="parent"
    app:layout_constraintTop_toBottomOf="@+id/appBarLayout" />
```
Efter det tog jag en skärmdump samt commitade och pushade mina ändringar till Github.
