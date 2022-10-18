package com.example.calculadora;

import androidx.appcompat.app.AppCompatActivity;

import android.os.Bundle;
import android.view.View;
import android.widget.Button;
import android.widget.EditText;
import android.widget.TextView;

public class MainActivity extends AppCompatActivity {

    @Override
    protected void onCreate(Bundle savedInstanceState) {
        super.onCreate(savedInstanceState);
        setContentView(R.layout.activity_main);

        EditText editText1 = (EditText) findViewById(R.id.editText01);
        EditText editText2 = (EditText) findViewById(R.id.editText02);
        TextView textView = (TextView) findViewById(R.id.textView01);
        Button button1 = (Button) findViewById(R.id.button01);
        Button button2 = (Button) findViewById(R.id.button02);
        Button button3 = (Button) findViewById(R.id.button03);
        Button button4 = (Button) findViewById(R.id.button04);

        button1.setOnClickListener(new View.OnClickListener(){
            public void onClick(View view) {
                float x = Float.parseFloat(editText1.getText().toString());
                float y = Float.parseFloat(editText2.getText().toString());
                float z = x + y;
                String aux = Float.toString(z);
                textView.setText(aux);
                editText1.getText().clear();
                editText2.getText().clear();
            }
        });

        button2.setOnClickListener(new View.OnClickListener(){
            public void onClick(View view) {
                float x = Float.parseFloat(editText1.getText().toString());
                float y = Float.parseFloat(editText2.getText().toString());
                float z = x - y;
                String aux = Float.toString(z);
                textView.setText(aux);
                editText1.getText().clear();
                editText2.getText().clear();
            }
        });

        button3.setOnClickListener(new View.OnClickListener(){
            public void onClick(View view) {
                float x = Float.parseFloat(editText1.getText().toString());
                float y = Float.parseFloat(editText2.getText().toString());
                float z = x * y;
                String aux = Float.toString(z);
                textView.setText(aux);
                editText1.getText().clear();
                editText2.getText().clear();
            }
        });

        button4.setOnClickListener(new View.OnClickListener(){
            public void onClick(View view) {
                float x = Float.parseFloat(editText1.getText().toString());
                float y = Float.parseFloat(editText2.getText().toString());
                float z = x / y;
                String aux = Float.toString(z);
                textView.setText(aux);
                editText1.getText().clear();
                editText2.getText().clear();
            }
        });
    }
}
