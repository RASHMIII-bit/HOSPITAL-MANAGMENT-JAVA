# HOSPITAL-MANAGMENT-JAVA
package hospital.management.system;

import javax.swing.*;
import java.awt.*;
import java.awt.event.ActionEvent;
import java.awt.event.ActionListener;

public class Reception extends JFrame {{::
n
    Reception(){

        JPanel panel = new JPanel();
        panel.setLayout(null);
        panel.setBounds(5,160 ,1525,670);
        panel.setBackground(new Color( 109,164,170));
        add(panel);

        JPanel panel1 = new JPanel();
        panel1.setLayout(null);
        panel1.setBounds(5,5,1525,1525);
        panel1.setBackground(new Color(109,164,170));
        add(panel1);

        ImageIcon i1 = new ImageIcon(ClassLoader.getSystemResource("icon/dr.png"));
        Image image = i1.getImage().getScaledInstance(150,150,Image.SCALE_DEFAULT);
        ImageIcon i2 = new ImageIcon(image);
        JLabel  label  = new JLabel(i2);
        label.setBounds(1300,0,250,250);
        panel1.add(label);


        ImageIcon i11  = new ImageIcon(ClassLoader.getSystemResource("icon/amb.png"));
        Image image1 = i11.getImage().getScaledInstance(300,100,Image.SCALE_DEFAULT);
        ImageIcon i22 = new ImageIcon(image1);
        JLabel label1 = new JLabel(i22);
        label.setBounds(1000,50,300,100);
        panel1.add(label1);

        JButton btn1 = new JButton("Add new patient");
        btn1.setBounds(30,15,200,30);
        btn1.setBackground(new Color(246,215,118));
        panel1.add(btn1);
        btn1.addActionListener(new ActionListener() {
            @Override
            public void actionPerformed(ActionEvent e) {
                new Login();

            }
        });
JButton btn2 = new JButton("room");
        btn2.setBounds(30,50,200,30);
        btn2.setBackground(new Color(246,215,118));
        panel1.add(btn2);
        btn2.addActionListener(new ActionListener() {
            @Override
            public void actionPerformed(ActionEvent e) {
                                   }
                               });

        JButton btn3 = new JButton("department");
        btn3.setBounds(30,100,200,30);
        btn3.setBackground(new Color(246,215,118));
        panel1.add(btn3);
        btn3.addActionListener(new ActionListener() {
            @Override
            public void actionPerformed(ActionEvent e) {
            }
        });

        JButton btn4 = new JButton("add empolyee info");
        btn4.setBounds(270,15,200,30);
        btn4.setBackground(new Color(246,215,118));
        panel1.add(btn4);
        btn4.addActionListener(new ActionListener() {
            @Override
            public void actionPerformed(ActionEvent e) {
            }
        });
        JButton btn5 = new JButton("patient info");
        btn5.setBounds(270,58,200,30);
        btn5.setBackground(new Color(246,215,118));
        panel1.add(btn5);
        btn5.addActionListener(new ActionListener() {
            @Override
            public void actionPerformed(ActionEvent e) {
            }
             JButton btn6 = new JButton("patient discharge");
        btn6.setBounds(270,100,200,30);
        btn6.setBackground(new Color(246,215,118));
        panel1.add(btn6);
        btn6.addActionListener(new ActionListener() {
            @Override
            public void actionPerformed(ActionEvent e) {
            }
        });

