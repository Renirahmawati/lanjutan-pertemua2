# lanjutan-pertemua2
yang folder do kelas
public class jangan {
    void jangan (){
        JOptionPane.showMessageDialog(null, "ngeyel");
    }
    
}

polder di jfrem
package pertemuan2;

/**
 *
 * @author acer
 */
public class objek extends javax.swing.JFrame {

    /**
     * Creates new form objek
     */
    public objek() {
        initComponents();
    }

    private void jButton1ActionPerformed(java.awt.event.ActionEvent evt) {                                         
    jangan o = new jangan(); 
    o.jangan();//TODO add your handling code here:
    }                                        


    // Variables declaration - do not modify                     
    private javax.swing.JButton jButton1;
    // End of variables declaration                   
}

untuk jframe objeknya
package pertemuan2;

/**
 *
 * @author acer
 */
public class reni extends javax.swing.JFrame {
double nilai1,nilai2;
    /**
     * Creates new form reni
     */
    public reni() {
        initComponents();
    }

        void penjumlahan(){
          
            int Nilai1=Integer.parseInt(jTextField1.getText());
            int Nilai2=Integer.parseInt(jTextField2.getText());
            
            int penjumlahan = Nilai1+Nilai2;
                    
             jLabel3.setText("hasil = "+penjumlahan);
        }
        void pengurangan(){
             int Nilai1=Integer.parseInt(jTextField1.getText());
            int Nilai2=Integer.parseInt(jTextField2.getText());
         
            int pengurangan = Nilai1-Nilai2;
            
            jLabel3.setText("hasil = "+pengurangan);
        }
        void perkalian(){
            int Nilai1=Integer.parseInt(jTextField1.getText());
            int Nilai2=Integer.parseInt(jTextField2.getText());
            
            int perkalian = Nilai1*Nilai2;
            
            jLabel3.setText("hasil ="+perkalian);
        }   
         void pembagian(){
             double Nilai1=Double.parseDouble(jTextField1.getText());
             double  Nilai2=Double.parseDouble(jTextField2.getText());
            
             double pembagian = Nilai1/Nilai2;
            
            jLabel3.setText("hasil ="+pembagian);
             }
            
package pertemuan2;

/**
 *
 * @author acer
 */
public class reni extends javax.swing.JFrame {
double nilai1,nilai2;
    /**
     * Creates new form reni
     */
    public reni() {
        initComponents();
    }

        void penjumlahan(){
          
            int Nilai1=Integer.parseInt(jTextField1.getText());
            int Nilai2=Integer.parseInt(jTextField2.getText());
            
            int penjumlahan = Nilai1+Nilai2;
                    
             jLabel3.setText("hasil = "+penjumlahan);
        }
        void pengurangan(){
             int Nilai1=Integer.parseInt(jTextField1.getText());
            int Nilai2=Integer.parseInt(jTextField2.getText());
         
            int pengurangan = Nilai1-Nilai2;
            
            jLabel3.setText("hasil = "+pengurangan);
        }
        void perkalian(){
            int Nilai1=Integer.parseInt(jTextField1.getText());
            int Nilai2=Integer.parseInt(jTextField2.getText());
            
            int perkalian = Nilai1*Nilai2;
            
            jLabel3.setText("hasil ="+perkalian);
        }   
         void pembagian(){
             double Nilai1=Double.parseDouble(jTextField1.getText());
             double  Nilai2=Double.parseDouble(jTextField2.getText());
            
             double pembagian = Nilai1/Nilai2;
            
            jLabel3.setText("hasil ="+pembagian);
             }
            
}
