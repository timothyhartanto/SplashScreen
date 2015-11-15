package com.example.proto.addme;


import android.app.Activity;
import android.content.Intent;
import android.os.Bundle;

public class SplashScreen extends Activity{
    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.addme);

        Thread logoTimer = new Thread(){
            @Override
            public void run() {
                try{
                    sleep(5000);
                    Intent i = new Intent("com.example.proto.TEST");
                    startActivity(i);
                }catch(InterruptedException e){
                    e.printStackTrace();
                }
                finally {
                    finish();
                }
            }
        };
        logoTimer.start();
    }
}
