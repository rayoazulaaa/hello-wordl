# hello-wordl
my firts program with Java.
hi, my name is Ramiro , i love Escuchar musica(to listen to music) i am from Mexíco.
i have no changes yet , because no he escrito una sola linea de codigo de codigo.
/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package classone;

import javax.swing.JOptionPane;

/**
 *
 * @author hogar
 */
public class ClassOneGUI extends javax.swing.JFrame {
    private int status = 0;
    /**
     * Creates new form ClassOneGUI
     */
    public ClassOneGUI() {
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

        lblSimbolos = new javax.swing.JLabel();
        cmbSimbolos = new javax.swing.JComboBox<>();
        lblEjercicio1 = new javax.swing.JLabel();
        lblDescripcion = new javax.swing.JLabel();
        jScrollPane1 = new javax.swing.JScrollPane();
        lstOperaciones = new javax.swing.JList<>();
        cmbDigitos = new javax.swing.JComboBox<>();
        lblDig1 = new javax.swing.JLabel();
        cmbDig2 = new javax.swing.JComboBox<>();
        lblDig2 = new javax.swing.JLabel();
        cmbSim2 = new javax.swing.JComboBox<>();
        lblSim2 = new javax.swing.JLabel();
        cmbDig3 = new javax.swing.JComboBox<>();
        lblDig3 = new javax.swing.JLabel();
        btnResult = new javax.swing.JButton();
        btnMas1 = new javax.swing.JButton();
        btnMas2 = new javax.swing.JButton();
        btnMas3 = new javax.swing.JButton();
        lblResultados = new javax.swing.JLabel();
        lblStepOne = new javax.swing.JLabel();
        lblStep2 = new javax.swing.JLabel();
        btnTwoDigs = new javax.swing.JButton();

        setDefaultCloseOperation(javax.swing.WindowConstants.EXIT_ON_CLOSE);

        lblSimbolos.setText("Simbolos");

        cmbSimbolos.setModel(new javax.swing.DefaultComboBoxModel<>(new String[] { "+", "=", "?" }));
        cmbSimbolos.setEnabled(false);

        lblEjercicio1.setText("Ejercicio 1");

        lblDescripcion.setText("Realiza las siguientes operaciones basicas");

        lstOperaciones.setModel(new javax.swing.AbstractListModel<String>() {
            String[] strings = { "4+5", "1+3+5", "o 3+1+5", "o 5+1+3", "o 1+5+3", "o 3+5+1", "1+3", "5+4", "5+3+1", "3+1" };
            public int getSize() { return strings.length; }
            public String getElementAt(int i) { return strings[i]; }
        });
        jScrollPane1.setViewportView(lstOperaciones);

        cmbDigitos.setModel(new javax.swing.DefaultComboBoxModel<>(new String[] { "0", "1", "2", "3", "4", "5", "6", "7", "8", "9" }));
        cmbDigitos.setEnabled(false);

        lblDig1.setText("digito 1");

        cmbDig2.setModel(new javax.swing.DefaultComboBoxModel<>(new String[] { "0", "1", "2", "3", "4", "5", "6", "7", "8", "9" }));
        cmbDig2.setEnabled(false);

        lblDig2.setText("digito 2");

        cmbSim2.setModel(new javax.swing.DefaultComboBoxModel<>(new String[] { "+", "=", "?" }));
        cmbSim2.setEnabled(false);

        lblSim2.setText("Simbolos 2");

        cmbDig3.setModel(new javax.swing.DefaultComboBoxModel<>(new String[] { "0", "1", "2", "3", "4", "5", "6", "7", "8", "9", "?" }));
        cmbDig3.setEnabled(false);
        cmbDig3.addItemListener(new java.awt.event.ItemListener() {
            public void itemStateChanged(java.awt.event.ItemEvent evt) {
                cmbDig3ItemStateChanged(evt);
            }
        });

        lblDig3.setText("digito 3");

        btnResult.setText("= ?");
        btnResult.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btnResultActionPerformed(evt);
            }
        });

        btnMas1.setText("+");
        btnMas1.setEnabled(false);
        btnMas1.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btnMas1ActionPerformed(evt);
            }
        });

        btnMas2.setText("+");
        btnMas2.setEnabled(false);
        btnMas2.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btnMas2ActionPerformed(evt);
            }
        });

        btnMas3.setText("+");
        btnMas3.setEnabled(false);
        btnMas3.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btnMas3ActionPerformed(evt);
            }
        });

        lblStepOne.setText("step one -------------------------------");

        lblStep2.setText("Step two -------------------------------");

        btnTwoDigs.setText("=");
        btnTwoDigs.setEnabled(false);
        btnTwoDigs.addActionListener(new java.awt.event.ActionListener() {
            public void actionPerformed(java.awt.event.ActionEvent evt) {
                btnTwoDigsActionPerformed(evt);
            }
        });

        javax.swing.GroupLayout layout = new javax.swing.GroupLayout(getContentPane());
        getContentPane().setLayout(layout);
        layout.setHorizontalGroup(
            layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
            .addGroup(layout.createSequentialGroup()
                .addContainerGap()
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING, false)
                    .addComponent(jScrollPane1, javax.swing.GroupLayout.PREFERRED_SIZE, 236, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addComponent(lblDescripcion)
                    .addGroup(javax.swing.GroupLayout.Alignment.TRAILING, layout.createSequentialGroup()
                        .addComponent(lblEjercicio1)
                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                        .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                            .addComponent(lblStepOne)
                            .addGroup(layout.createSequentialGroup()
                                .addComponent(btnMas1)
                                .addGap(18, 18, 18)
                                .addComponent(btnMas2)
                                .addGap(18, 18, 18)
                                .addComponent(btnMas3)))
                        .addGap(2, 2, 2)))
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addGroup(layout.createSequentialGroup()
                        .addGap(18, 18, 18)
                        .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING, false)
                            .addComponent(lblStep2, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                            .addComponent(btnResult, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                            .addGroup(layout.createSequentialGroup()
                                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                                    .addGroup(layout.createSequentialGroup()
                                        .addComponent(cmbDig2, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                                        .addComponent(lblDig2))
                                    .addGroup(layout.createSequentialGroup()
                                        .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING, false)
                                            .addComponent(cmbDigitos, 0, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                                            .addComponent(cmbSimbolos, 0, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE))
                                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                                        .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                                            .addComponent(lblSimbolos)
                                            .addComponent(lblDig1)))
                                    .addGroup(layout.createSequentialGroup()
                                        .addComponent(cmbSim2, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                                        .addComponent(lblSim2))
                                    .addGroup(layout.createSequentialGroup()
                                        .addComponent(cmbDig3, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                                        .addComponent(lblDig3)))
                                .addGap(18, 18, 18)
                                .addComponent(btnTwoDigs, javax.swing.GroupLayout.PREFERRED_SIZE, 48, javax.swing.GroupLayout.PREFERRED_SIZE)))
                        .addContainerGap(javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE))
                    .addGroup(javax.swing.GroupLayout.Alignment.TRAILING, layout.createSequentialGroup()
                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED, javax.swing.GroupLayout.DEFAULT_SIZE, Short.MAX_VALUE)
                        .addComponent(lblResultados, javax.swing.GroupLayout.PREFERRED_SIZE, 71, javax.swing.GroupLayout.PREFERRED_SIZE)
                        .addGap(29, 29, 29))))
        );
        layout.setVerticalGroup(
            layout.createParallelGroup(javax.swing.GroupLayout.Alignment.TRAILING)
            .addGroup(javax.swing.GroupLayout.Alignment.LEADING, layout.createSequentialGroup()
                .addGap(14, 14, 14)
                .addComponent(lblStepOne)
                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                    .addComponent(lblEjercicio1)
                    .addComponent(btnMas1, javax.swing.GroupLayout.PREFERRED_SIZE, 19, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addComponent(btnMas2, javax.swing.GroupLayout.PREFERRED_SIZE, 19, javax.swing.GroupLayout.PREFERRED_SIZE)
                    .addComponent(btnMas3, javax.swing.GroupLayout.PREFERRED_SIZE, 19, javax.swing.GroupLayout.PREFERRED_SIZE))
                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                .addComponent(lblDescripcion)
                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                .addComponent(jScrollPane1))
            .addGroup(javax.swing.GroupLayout.Alignment.LEADING, layout.createSequentialGroup()
                .addGap(30, 30, 30)
                .addComponent(lblResultados, javax.swing.GroupLayout.PREFERRED_SIZE, 42, javax.swing.GroupLayout.PREFERRED_SIZE)
                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.UNRELATED)
                .addComponent(lblStep2)
                .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.LEADING)
                    .addGroup(layout.createSequentialGroup()
                        .addGap(11, 11, 11)
                        .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                            .addComponent(cmbDigitos, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                            .addComponent(lblDig1))
                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                        .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                            .addComponent(cmbSimbolos, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                            .addComponent(lblSimbolos))
                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                        .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                            .addComponent(cmbDig2, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                            .addComponent(lblDig2))
                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                        .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                            .addComponent(cmbSim2, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                            .addComponent(lblSim2))
                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                        .addGroup(layout.createParallelGroup(javax.swing.GroupLayout.Alignment.BASELINE)
                            .addComponent(cmbDig3, javax.swing.GroupLayout.PREFERRED_SIZE, javax.swing.GroupLayout.DEFAULT_SIZE, javax.swing.GroupLayout.PREFERRED_SIZE)
                            .addComponent(lblDig3)))
                    .addGroup(javax.swing.GroupLayout.Alignment.TRAILING, layout.createSequentialGroup()
                        .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                        .addComponent(btnTwoDigs, javax.swing.GroupLayout.PREFERRED_SIZE, 169, javax.swing.GroupLayout.PREFERRED_SIZE)))
                .addPreferredGap(javax.swing.LayoutStyle.ComponentPlacement.RELATED)
                .addComponent(btnResult)
                .addContainerGap(20, Short.MAX_VALUE))
        );

        pack();
    }// </editor-fold>                        

    private void btnMas1ActionPerformed(java.awt.event.ActionEvent evt) {                                        
        this.cmbDigitos.setSelectedItem("4");
        this.cmbSimbolos.setSelectedItem("+");
        this.cmbSimbolos.setEnabled(false);
        this.cmbDig2.setSelectedItem("5");
        this.cmbSim2.setSelectedItem("=");
        this.cmbSim2.setEnabled(false);
        this.cmbDig3.setSelectedItem("?");
        this.cmbDig3.setEnabled(false);
        this.btnMas1.setEnabled(false);
        this.cmbDig2.setEnabled(false);
        this.cmbDigitos.setEnabled(false);
        this.btnTwoDigs.setEnabled(true);
        this.btnResult.setEnabled(false);
        this.status++;
    }                                       

    private void cmbDig3ItemStateChanged(java.awt.event.ItemEvent evt) {                                         

    }                                        

    private void btnTwoDigsActionPerformed(java.awt.event.ActionEvent evt) {                                           
        int numero_1 = Integer.parseInt(this.cmbDigitos.getSelectedItem().toString());
        int numero_2 = Integer.parseInt(this.cmbDig2.getSelectedItem().toString());
        this.lblResultados.setText(Integer.toString(numero_1 + numero_2));
        this.btnResult.setEnabled(true);
        JOptionPane.showMessageDialog(null, this.status);
        switch(status){
            case 1 : this.btnResult.setEnabled(false);this.btnMas1.setEnabled(false);this.btnMas2.setEnabled(true);break;
            case 2 : this.btnResult.setEnabled(false);this.btnMas1.setEnabled(false);this.btnMas2.setEnabled(false);this.btnMas3.setEnabled(true);break;
            case 3 : this.btnMas3.setEnabled(false);this.btnTwoDigs.setEnabled(false);this.btnResult.setEnabled(true);break;
            case 4 : this.status = 0; JOptionPane.showMessageDialog(null, "Se Reinicio el contador");break;
        }
        this.btnTwoDigs.setEnabled(false);
        
    }                                          

    private void btnMas2ActionPerformed(java.awt.event.ActionEvent evt) {                                        
        this.cmbDigitos.setSelectedItem("1");
        this.btnMas2.setEnabled(false);
        this.cmbSimbolos.setSelectedItem("+");
        this.cmbDig2.setSelectedItem("3");
        this.cmbSim2.setSelectedItem("=");
        this.cmbDig3.setSelectedItem("?");
        this.btnTwoDigs.setEnabled(true);
        this.btnResult.setEnabled(false);
        this.status++;
    }                                       

    private void btnMas3ActionPerformed(java.awt.event.ActionEvent evt) {                                        
        this.cmbDigitos.setSelectedItem("1");
        this.cmbSimbolos.setSelectedItem("+");
        this.cmbDig2.setSelectedItem("3");
        this.cmbSim2.setSelectedItem("+");
        this.cmbDig3.setSelectedItem("5");
        this.btnMas3.setEnabled(false);
        this.btnTwoDigs.setEnabled(true);
        this.btnResult.setEnabled(false);
        this.status++;
    }                                       

    private void btnResultActionPerformed(java.awt.event.ActionEvent evt) {                                          
        int numero_1,numero_2,numero_3 = 0;
        this.cmbSim2.setSelectedItem("+");
        this.cmbDig3.setSelectedItem("5");
        this.cmbDig2.setSelectedItem("3");
        this.cmbDigitos.setSelectedItem("1");
        if(this.status == 0){
            numero_1 = Integer.parseInt(this.cmbDigitos.getSelectedItem().toString());
            numero_2 = Integer.parseInt(this.cmbDig2.getSelectedItem().toString());
            numero_3 = Integer.parseInt(this.cmbDig3.getSelectedItem().toString());
            this.lblResultados.setText(Integer.toString(numero_1 + numero_2 + numero_3));
        }else{
            numero_1 = Integer.parseInt(this.cmbDigitos.getSelectedItem().toString());
            numero_2 = Integer.parseInt(this.cmbDig2.getSelectedItem().toString());
            if(this.cmbDig3.getSelectedItem().toString().equals("?")){
                numero_3 = 5;
            }else{
                numero_3 = Integer.parseInt(this.cmbDig3.getSelectedItem().toString());
            }
        }
        this.lblResultados.setText(Integer.toString(numero_1 + numero_2 + numero_3));
        JOptionPane.showMessageDialog(null, "sigue dando click a los botones");
        this.btnMas1.setEnabled(true); 
        this.btnResult.setEnabled(false);
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
            java.util.logging.Logger.getLogger(ClassOneGUI.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        } catch (InstantiationException ex) {
            java.util.logging.Logger.getLogger(ClassOneGUI.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        } catch (IllegalAccessException ex) {
            java.util.logging.Logger.getLogger(ClassOneGUI.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        } catch (javax.swing.UnsupportedLookAndFeelException ex) {
            java.util.logging.Logger.getLogger(ClassOneGUI.class.getName()).log(java.util.logging.Level.SEVERE, null, ex);
        }
        //</editor-fold>

        /* Create and display the form */
        java.awt.EventQueue.invokeLater(new Runnable() {
            public void run() {
                new ClassOneGUI().setVisible(true);
            }
        });
    }

    // Variables declaration - do not modify                     
    private javax.swing.JButton btnMas1;
    private javax.swing.JButton btnMas2;
    private javax.swing.JButton btnMas3;
    private javax.swing.JButton btnResult;
    private javax.swing.JButton btnTwoDigs;
    private javax.swing.JComboBox<String> cmbDig2;
    private javax.swing.JComboBox<String> cmbDig3;
    private javax.swing.JComboBox<String> cmbDigitos;
    private javax.swing.JComboBox<String> cmbSim2;
    private javax.swing.JComboBox<String> cmbSimbolos;
    private javax.swing.JScrollPane jScrollPane1;
    private javax.swing.JLabel lblDescripcion;
    private javax.swing.JLabel lblDig1;
    private javax.swing.JLabel lblDig2;
    private javax.swing.JLabel lblDig3;
    private javax.swing.JLabel lblEjercicio1;
    private javax.swing.JLabel lblResultados;
    private javax.swing.JLabel lblSim2;
    private javax.swing.JLabel lblSimbolos;
    private javax.swing.JLabel lblStep2;
    private javax.swing.JLabel lblStepOne;
    private javax.swing.JList<String> lstOperaciones;
    // End of variables declaration                   
}
