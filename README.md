# index.html

Home » Android_Studio » Cara Membuat Tampilan Login Seperti Facebook Lite di Android Studio

Cara Membuat Tampilan Login Seperti Facebook Lite di Android Studio


Facebook merupakan salah satu sosial media paling banyak digunakan di Indonesia. Facebook kini memiliki aplikasi mobile yang diberi nama facebook lite, aplikasi ini dikhususkan untuk pengguna yang menginginkan performa cepat dengan ukuran ringan.

Pada postingan kali ini saya ingin membagikan desain tampilan login dari Facebook lite yang telah saya buat. Berikut bentuk tampilan yang telah saya buat :




Untuk membuat tampilan seperti di atas anda hanya perlu mengedit layout teman-teman dengan kode seperti berikut :





<?xml version="1.0" encoding="utf-8"?>
<RelativeLayout xmlns:android="http://schemas.android.com/apk/res/android"
    xmlns:app="http://schemas.android.com/apk/res-auto"
    xmlns:tools="http://schemas.android.com/tools"
    android:layout_width="match_parent"
    android:layout_height="match_parent"
    tools:context=".MainActivity">

    <LinearLayout
        android:layout_width="match_parent"
        android:layout_height="match_parent"
        android:orientation="vertical">

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:background="@color/biru"
            android:gravity="center"
            android:orientation="vertical"
            android:padding="10dp">

            <TextView
                android:id="@+id/textView"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:gravity="center"
                android:text="Coding Rakitan"
                android:textColor="@android:color/white" />

        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="wrap_content"
            android:padding="10dp"
            android:orientation="vertical">

            <TextView
                android:id="@+id/textView2"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:textColor="@android:color/black"
                android:text="Nomor Ponsel atau Email" />

            <EditText
                android:id="@+id/editText"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginBottom="20dp"
                android:background="@android:drawable/editbox_background"
                android:ems="10"
                android:padding="10dp"
                android:inputType="textPersonName"
                android:text="" />

            <TextView
                android:id="@+id/textView3"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:textColor="@android:color/black"
                android:text="Kata Sandi" />

            <EditText
                android:id="@+id/editText2"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginBottom="20dp"
                android:background="@android:drawable/editbox_background"
                android:ems="10"
                android:padding="10dp"
                android:inputType="textPassword" />

            <Button
                android:id="@+id/button"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:background="@color/biru_button"
                android:textColor="@android:color/white"
                android:text="Masuk" />

            <TextView
                android:id="@+id/textView4"
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:layout_marginTop="20dp"
                android:textColor="@color/biru_button"
                android:text="Lupa kata sandi Anda ?" />
        </LinearLayout>

        <LinearLayout
            android:layout_width="match_parent"
            android:layout_height="match_parent"
            android:background="@color/abu_abu"
            android:orientation="vertical">

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:orientation="vertical"
                android:layout_weight="1"
                android:padding="10dp">

                <TextView
                    android:id="@+id/textView5"
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:gravity="center"
                    android:text="atau" />

                <Button
                    android:id="@+id/button2"
                    android:layout_width="wrap_content"
                    android:layout_height="wrap_content"
                    android:layout_gravity="center"
                    android:layout_marginTop="10dp"
                    android:layout_marginBottom="25dp"
                    android:background="@color/hijau"
                    android:padding="10dp"
                    android:text="Buat Akun Baru"
                    android:textColor="@android:color/white" />

                <TextView
                    android:id="@+id/textView6"
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:layout_marginBottom="10dp"
                    android:paddingLeft="5dp"
                    android:text="Bahasa Indonesia" />

                <TextView
                    android:id="@+id/textView7"
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:layout_marginBottom="10dp"
                    android:paddingLeft="5dp"
                    android:text="Bahasa Jawa"
                    android:textColor="@color/biru_button" />

                <TextView
                    android:id="@+id/textView8"
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:layout_marginBottom="10dp"
                    android:paddingLeft="5dp"
                    android:text="English"
                    android:textColor="@color/biru_button" />

                <TextView
                    android:id="@+id/textView9"
                    android:layout_width="match_parent"
                    android:layout_height="wrap_content"
                    android:layout_marginBottom="10dp"
                    android:text="Bahasa Lainnya"
                    android:textColor="@color/biru_button" />

            </LinearLayout>

            <LinearLayout
                android:layout_width="match_parent"
                android:layout_height="wrap_content"
                android:padding="10dp"
                android:background="@color/biru"
                android:layout_gravity="bottom"
                android:orientation="horizontal">

                <LinearLayout
                    android:layout_width="match_parent"
                    android:layout_height="match_parent"
                    android:layout_weight="1"
                    android:gravity="left"
                    android:orientation="vertical">

                    <TextView
                        android:id="@+id/textView10"
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        android:layout_weight="1"
                        android:text="Bantuan"
                        android:textColor="@android:color/white" />
                </LinearLayout>

                <LinearLayout
                    android:layout_width="match_parent"
                    android:layout_height="match_parent"
                    android:layout_weight="1"
                    android:gravity="right"
                    android:orientation="vertical">

                    <TextView
                        android:id="@+id/textView11"
                        android:layout_width="wrap_content"
                        android:layout_height="wrap_content"
                        android:layout_weight="1"
                        android:gravity="right"
                        android:text="Keluar"
                        android:textColor="@android:color/white" />
                </LinearLayout>
            </LinearLayout>
        </LinearLayout>

    </LinearLayout>

</RelativeLayout>
