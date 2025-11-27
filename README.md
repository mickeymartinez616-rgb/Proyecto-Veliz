package bancosapp;

import javax.swing.SwingUtilities;

public class MainApp {
    public static void main(String[] args) {
        SwingUtilities.invokeLater(() -> {
            // Inicia la aplicación mostrando el formulario de Bancos
            FrmBancos formInicial = new FrmBancos();
            formInicial.setVisible(true);
            formInicial.setLocationRelativeTo(null); 
        });
    }
}
