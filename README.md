package week18.Tutorial.workshop;


import javax.swing.JFrame;
import javax.swing.JLabel;
import javax.swing.JTextField;
import javax.swing.JButton;

public class Form {
    public static void main(String[] agrs)
    {
        JFrame frame = new JFrame("Registration");
        frame.setSize(600,500);
        frame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
        frame.setLocationRelativeTo(null);
        frame.setResizable(false);
        frame.setLayout(null);


        JLabel userLbl = new JLabel();
        userLbl.setText("Register User");
        userLbl.setBounds(220, 30, 100, 20);
        //firstname
        JLabel firstLbl = new JLabel();
        firstLbl.setText("First Name: ");
        firstLbl.setBounds(20,50,90,50);
       JTextField firstName = new JTextField();
       firstName.setBounds(115, 60,100,30);
       //lastname
       JLabel lastLbl = new JLabel();
       lastLbl.setText("Last Name: ");
       lastLbl.setBounds(20,90,90,50);
      JTextField lastName = new JTextField();
      lastName.setBounds(115, 100,100,30);
       //EmailAddress
       JLabel emailLbl = new JLabel();
       emailLbl.setText("Email Address: ");
       emailLbl.setBounds(20,130,200,50);
      JTextField emailAddress = new JTextField();
      emailAddress.setBounds(115, 140,100,30);
      //Username
      JLabel usernameLbl = new JLabel();
      usernameLbl.setText("User Name: ");
      usernameLbl.setBounds(300,50,90,50);
     JTextField userNameTF = new JTextField();
     userNameTF.setBounds(405, 60,100,30);
     //password
     JLabel passwordLbl = new JLabel();
     passwordLbl.setText("Password: ");
     passwordLbl.setBounds(300,80,90,50);
    JTextField passwordTF = new JTextField();
    passwordTF.setBounds(405, 90,100,30);
    //Mobilenumber
    JLabel MobilenumberLbl = new JLabel();
    MobilenumberLbl.setText("Mobile number: ");
    MobilenumberLbl.setBounds(300,110,130,50);
   JTextField mobileNumberTF = new JTextField();
   mobileNumberTF.setBounds(405, 120,100,30);
   //RegisterButton
   JButton registerBtn=new JButton("Register");
        registerBtn.setBounds(220,200,100,30);



        frame.add(userLbl);
        frame.add(firstLbl);
        frame.add(firstName);
        frame.add(lastLbl);
        frame.add(lastName);
        frame.add(emailLbl);
        frame.add(emailAddress);
        frame.add(usernameLbl);
        frame.add(userNameTF);
        frame.add(passwordLbl);
        frame.add(passwordTF);
        frame.add(MobilenumberLbl);
        frame.add(mobileNumberTF);
        frame.add(registerBtn);

        frame.setVisible(true);
    }
}
