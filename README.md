# Aplikasi Konversi Suhu

# Deskripsi
Konversi Suhu adalah aplikasi praktis yang dirancang untuk membantu pengguna mengonversi suhu antara berbagai skala umum, seperti Celsius, Fahrenheit, dan Kelvin. Aplikasi ini memudahkan pengguna untuk menghitung konversi suhu dengan cepat dan akurat, baik untuk keperluan ilmiah, pendidikan, maupun sehari-hari. Dengan antarmuka yang intuitif, pengguna hanya perlu memasukkan nilai suhu dan memilih satuan awal serta satuan tujuan, lalu aplikasi akan menampilkan hasil konversinya.

## Coding Java Frame Aplikasi Konversi Suhu
```java


import javax.swing.JOptionPane;
/**
 *
 * @author User
 */
public class AplikasiKonversiSuhu extends javax.swing.JFrame {

    /**
     * Creates new form AplikasiKonversiSuhu
     */
    public AplikasiKonversiSuhu() {
        initComponents();
    }

    /**
     * This method is called from within the constructor to initialize the form.
     * WARNING: Do NOT modify this code. The content of this method is always
     * regenerated by the Form Editor.
     */
    @SuppressWarnings("unchecked")
    // <editor-fold defaultstate="collapsed" desc="Generated Code">                          
    private void initComponents() {

        buttonGroup1 = new javax.swing.ButtonGroup();
        buttonGroup2 = new javax.swing.ButtonGroup();
        buttonGroup3 = new javax.swing.ButtonGroup();
        buttonGroup4 = new javax.swing.ButtonGroup();
        JOptionPanel = new javax.swing.JPanel();
        jLabel1 = new javax.swing.JLabel();
        jLabel2 = new javax.swing.JLabel();
        inputTextField = new javax.swing.JTextField();
        comboBoxSkala = new javax.swing.JComboBox<>();
        jButton1 = new javax.swing.JButton();
        hasilLabel = new javax.swing.JLabel();
        jRadioButton1 = new javax.swing.JRadioButton();
        jRadioButton2 = new javax.swing.JRadioButton();
        jRadioButton3 = new javax.swing.JRadioButton();
        jRadioButton4 = new javax.swing.JRadioButton();
        jLabel3 = new javax.swing.JLabel();
        jLabel4 = new javax.swing.JLabel();
        jLabel5 = new javax.swing.JLabel();

        setDefaultCloseOperation(javax.swing.WindowConstants.EXIT_ON_CLOSE);

        jLabel1.setFont(new java.awt.Font("Tahoma", 1, 24)); // NOI18N
        jLabel1.setText("APLIKASI KONVERSI SUHU");

        jLabel2.setFont(new java.awt.Font("Tahoma", 1, 16)); // NOI18N
        jLabel2.setText("Masukkan Suhu : ");

        inputTextField.addKeyListener(new java.awt.event.KeyAdapter() {
            public void keyTyped(java.awt.event.KeyEvent evt) {
                inputTextFieldKeyTyped(evt);
            }
        });

        comboBoxSkala.setModel(new javax.swing.DefaultComboBoxModel<>(new String[] { "Pilih", "Celcius", "Fahrenheit", "Reamur", "Kelvin" }));
        comboBoxSkala.addItemListener(new java.awt.event.ItemListener() {
            public void itemStateChanged(java.awt.event.ItemEvent evt) {
                comboBoxSkalaItemStateChanged(evt);
            }
        });
        comboBoxSkala.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                comboBoxSkalaActionPerformed(evt);
            }
        });

        jButton1.setText("Konversi");
        jButton1.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jButton1ActionPerformed(evt);
            }
        });

        buttonGroup1.add(jRadioButton1);
        jRadioButton1.setFont(new java.awt.Font("Tahoma", 1, 15)); // NOI18N
        jRadioButton1.setText("Celcius");
        jRadioButton1.setName(""); // NOI18N
        jRadioButton1.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jRadioButton1ActionPerformed(evt);
            }
        });

        buttonGroup1.add(jRadioButton2);
        jRadioButton2.setFont(new java.awt.Font("Tahoma", 1, 15)); // NOI18N
        jRadioButton2.setText("Fahrenheit");
        jRadioButton2.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jRadioButton2ActionPerformed(evt);
            }
        });

        buttonGroup1.add(jRadioButton3);
        jRadioButton3.setFont(new java.awt.Font("Tahoma", 1, 15)); // NOI18N
        jRadioButton3.setText("Reamur");
        jRadioButton3.setBorderPainted(true);
        jRadioButton3.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                jRadioButton3ActionPerformed(evt);
            }
        });

        buttonGroup1.add(jRadioButton4);
        jRadioButton4.setFont(new java.awt.Font("Tahoma", 1, 15)); // NOI18N
        jRadioButton4.setText("Kelvin");

        jLabel3.setFont(new java.awt.Font("Times New Roman", 1, 15)); // NOI18N
        jLabel3.setText("Nama : Muhammad Afriza Rizqi Pramudya");

        jLabel4.setFont(new java.awt.Font("Times New Roman", 1, 15)); // NOI18N
        jLabel4.setText("Kelas : 5B Reguler Pagi Banjarmasin");

        jLabel5.setFont(new java.awt.Font("Times New Roman", 1, 15)); // NOI18N
        jLabel5.setText("Npm : 2210010679");

        javax.swing.GroupLayout JOptionPanelLayout = new javax.swing.GroupLayout(JOptionPanel);
        JOptionPanel.setLayout(JOptionPanelLayout);
        JOptionPanelLayout.setHorizontalGroup(
            JOptionPanelLayout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(javax.swing.GroupLayout.Alignment.TRAILING, JOptionPanelLayout.createSequentialGroup()
                .addContainerGap(javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                .addComponent(jLabel1)
                .addGap(193, 193, 193))
            .addGroup(JOptionPanelLayout.createSequentialGroup()
                .addGap(34, 34, 34)
                .addGroup(JOptionPanelLayout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addComponent(jLabel3)
                    .addGroup(JOptionPanelLayout.createSequentialGroup()
                        .addGroup(JOptionPanelLayout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                            .addGroup(JOptionPanelLayout.createSequentialGroup()
                                .addGroup(JOptionPanelLayout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                                    .addGroup(JOptionPanelLayout.createSequentialGroup()
                                        .addComponent(jLabel2)
                                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                                        .addComponent(inputTextField, javax.swing.GroupLayout.PREFERRED_SIZE, 151, javax.swing.GroupLayout.PREFERRED_SIZE)
                                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                                        .addComponent(jRadioButton1, javax.swing.GroupLayout.PREFERRED_SIZE, 126, javax.swing.GroupLayout.PREFERRED_SIZE))
                                    .addGroup(JOptionPanelLayout.createSequentialGroup()
                                        .addGap(280, 280, 280)
                                        .addComponent(jButton1))
                                    .addGroup(JOptionPanelLayout.createSequentialGroup()
                                        .addGap(149, 149, 149)
                                        .addComponent(comboBoxSkala, javax.swing.GroupLayout.PREFERRED_SIZE, 151, javax.swing.GroupLayout.PREFERRED_SIZE)
                                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                                        .addComponent(jRadioButton2, javax.swing.GroupLayout.PREFERRED_SIZE, 126, javax.swing.GroupLayout.PREFERRED_SIZE)))
                                .addGap(47, 47, 47))
                            .addGroup(JOptionPanelLayout.createSequentialGroup()
                                .addGroup(JOptionPanelLayout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                                    .addComponent(jLabel5)
                                    .addComponent(jLabel4))
                                .addGap(219, 219, 219)
                                .addComponent(hasilLabel, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.UNRELATED)))
                        .addGroup(JOptionPanelLayout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                            .addComponent(jRadioButton3, javax.swing.GroupLayout.PREFERRED_SIZE, 151, javax.swing.GroupLayout.PREFERRED_SIZE)
                            .addComponent(jRadioButton4, javax.swing.GroupLayout.PREFERRED_SIZE, 151, javax.swing.GroupLayout.PREFERRED_SIZE))))
                .addContainerGap(21, Short.MAX_VALUE))
        );
        JOptionPanelLayout.setVerticalGroup(
            JOptionPanelLayout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(JOptionPanelLayout.createSequentialGroup()
                .addContainerGap()
                .addComponent(jLabel1)
                .addGap(28, 28, 28)
                .addGroup(JOptionPanelLayout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(jLabel2)
                    .addComponent(inputTextField, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addComponent(jRadioButton1)
                    .addComponent(jRadioButton3))
                .addGap(23, 23, 23)
                .addGroup(JOptionPanelLayout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(comboBoxSkala, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addComponent(jRadioButton2)
                    .addComponent(jRadioButton4))
                .addGap(33, 33, 33)
                .addComponent(jButton1)
                .addGap(11, 11, 11)
                .addGroup(JOptionPanelLayout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addGroup(JOptionPanelLayout.createSequentialGroup()
                        .addGap(79, 79, 79)
                        .addComponent(hasilLabel, javax.swing.GroupLayout.PREFERRED_SIZE, 20, javax.swing.GroupLayout.PREFERRED_SIZE)
                        .addContainerGap(javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE))
                    .addGroup(JOptionPanelLayout.createSequentialGroup()
                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED, 36, Short.MAX_VALUE)
                        .addComponent(jLabel3)
                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                        .addComponent(jLabel5)
                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                        .addComponent(jLabel4)
                        .addGap(59, 59, 59))))
        );

        javax.swing.GroupLayout layout = new javax.swing.GroupLayout(getContentPane());
        getContentPane().setLayout(layout);
        layout.setHorizontalGroup(
            layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addComponent(JOptionPanel, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
        );
        layout.setVerticalGroup(
            layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(layout.createSequentialGroup()
                .addContainerGap()
                .addComponent(JOptionPanel, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                .addContainerGap())
        );

        pack();
    }// </editor-fold>                        

    private void comboBoxSkalaActionPerformed(java.awt.event.ActionEvent evt) {                                              
                                              

    }                                             

    private void jButton1ActionPerformed(java.awt.event.ActionEvent evt) {                                         
                                        
    try {
    double suhuInput = Double.parseDouble(inputTextField.getText());
    String skalaInput = (String) comboBoxSkala.getSelectedItem();
    double hasilKonversi = 0;
    String skalaTujuan = "";

    // Pilih konversi berdasarkan skala input yang dipilih
    if (skalaInput.equals("Celcius")) {
        if (jRadioButton3.isSelected()) {
            hasilKonversi = suhuInput * 4 / 5; // Celcius ke Reamur
            skalaTujuan = "Reamur";
        } else if (jRadioButton2.isSelected()) {
            hasilKonversi = (suhuInput * 9 / 5) + 32; // Celcius ke Fahrenheit
            skalaTujuan = "Fahrenheit";
        } else if (jRadioButton4.isSelected()) {
            hasilKonversi = suhuInput + 273.15; // Celcius ke Kelvin
            skalaTujuan = "Kelvin";
        }
    } else if (skalaInput.equals("Fahrenheit")) {
        if (jRadioButton1.isSelected()) {
            hasilKonversi = (suhuInput - 32) * 5 / 9; // Fahrenheit ke Celcius
            skalaTujuan = "Celcius";
        } else if (jRadioButton3.isSelected()) {
            hasilKonversi = (suhuInput - 32) * 4 / 9; // Fahrenheit ke Reamur
            skalaTujuan = "Reamur";
        } else if (jRadioButton4.isSelected()) {
            hasilKonversi = (suhuInput - 32) * 5 / 9 + 273.15; // Fahrenheit ke Kelvin
            skalaTujuan = "Kelvin";
        }
    } else if (skalaInput.equals("Reamur")) {
        if (jRadioButton1.isSelected()) {
            hasilKonversi = suhuInput * 5 / 4; // Reamur ke Celcius
            skalaTujuan = "Celcius";
        } else if (jRadioButton2.isSelected()) {
            hasilKonversi = (suhuInput * 9 / 4) + 32; // Reamur ke Fahrenheit
            skalaTujuan = "Fahrenheit";
        } else if (jRadioButton4.isSelected()) {
            hasilKonversi = (suhuInput * 5 / 4) + 273.15; // Reamur ke Kelvin
            skalaTujuan = "Kelvin";
        }
    } else if (skalaInput.equals("Kelvin")) {
        if (jRadioButton1.isSelected()) {
            hasilKonversi = suhuInput - 273.15; // Kelvin ke Celcius
            skalaTujuan = "Celcius";
        } else if (jRadioButton2.isSelected()) {
            hasilKonversi = (suhuInput - 273.15) * 9 / 5 + 32; // Kelvin ke Fahrenheit
            skalaTujuan = "Fahrenheit";
        } else if (jRadioButton3.isSelected()) {
            hasilKonversi = (suhuInput - 273.15) * 4 / 5; // Kelvin ke Reamur
            skalaTujuan = "Reamur";
        }
    }

    // Tampilkan hasil konversi
    hasilLabel.setText("Hasil Konversi: " + hasilKonversi + " " + skalaTujuan);
} catch (NumberFormatException e) {
    // Menampilkan pesan error jika input bukan angka
    JOptionPane.showMessageDialog(this, "Masukkan angka terlebih dahulu!", "Input Error", JOptionPane.ERROR_MESSAGE);
    inputTextField.setText("");
}



    }                                        

    private void inputTextFieldKeyTyped(java.awt.event.KeyEvent evt) {                                        
                                      
    char karakter = evt.getKeyChar();
    
    // Memeriksa apakah karakter bukan angka atau titik desimal
    if (!Character.isDigit(karakter) && karakter != '.') {
        evt.consume(); // Mengabaikan karakter yang tidak valid
    }

    }                                       

    private void comboBoxSkalaItemStateChanged(java.awt.event.ItemEvent evt) {                                               
        // TODO add your handling code here:
    }                                              

    private void jRadioButton1ActionPerformed(java.awt.event.ActionEvent evt) {                                              
        // TODO add your handling code here:
    }                                             

    private void jRadioButton3ActionPerformed(java.awt.event.ActionEvent evt) {                                              
        // TODO add your handling code here:
    }                                             

    private void jRadioButton2ActionPerformed(java.awt.event.ActionEvent evt) {                                              
        // TODO add your handling code here:
    }                                             

    /**
     * @param args the command line arguments
     */
    public static void main(String args[]) {
        /* Set the Nimbus look and feel */
        //<editor-fold defaultstate="collapsed" desc=" Look and feel setting code (optional) ">
        /* If Nimbus (introduced in Java SE 6) is not available, stay with the default look and feel.
         * For details see http://download.oracle.com/javase/tutorial/uiswing/lookandfeel/plaf.html 
         */
        try {
            for (javax.swing.UIManager.LookAndFeelInfo info : javax.swing.UIManager.getInstalledLookAndFeels()) {
                if ("Nimbus".equals(info.getName())) {
                    javax.swing.UIManager.setLookAndFeel(info.getClassName());
                    break;
                }
            }
        } catch (ClassNotFoundException ex) {
            java.util.logging.Logger.getLogger(AplikasiKonversiSuhu.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        } catch (InstantiationException ex) {
            java.util.logging.Logger.getLogger(AplikasiKonversiSuhu.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        } catch (IllegalAccessException ex) {
            java.util.logging.Logger.getLogger(AplikasiKonversiSuhu.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        } catch (javax.swing.UnsupportedLookAndFeelException ex) {
            java.util.logging.Logger.getLogger(AplikasiKonversiSuhu.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        }
        //</editor-fold>

        /* Create and display the form */
        java.awt.EventQueue.invokeLater(new Runnable() {
            public void run() {
                new AplikasiKonversiSuhu().setVisible(true);
            }
        });
    }

    // Variables declaration - do not modify                     
    private javax.swing.JPanel JOptionPanel;
    private javax.swing.ButtonGroup buttonGroup1;
    private javax.swing.ButtonGroup buttonGroup2;
    private javax.swing.ButtonGroup buttonGroup3;
    private javax.swing.ButtonGroup buttonGroup4;
    private javax.swing.JComboBox<String> comboBoxSkala;
    private javax.swing.JLabel hasilLabel;
    private javax.swing.JTextField inputTextField;
    private javax.swing.JButton jButton1;
    private javax.swing.JLabel jLabel1;
    private javax.swing.JLabel jLabel2;
    private javax.swing.JLabel jLabel3;
    private javax.swing.JLabel jLabel4;
    private javax.swing.JLabel jLabel5;
    private javax.swing.JRadioButton jRadioButton1;
    private javax.swing.JRadioButton jRadioButton2;
    private javax.swing.JRadioButton jRadioButton3;
    private javax.swing.JRadioButton jRadioButton4;
    // End of variables declaration                   
}



```

## Pembuat
Muhammad Afriza Rizqi Pramudya (2210010679) 5B

