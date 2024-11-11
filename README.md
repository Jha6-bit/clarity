# clarity
import javax.swing.*;
import java.awt.*;

public class BoldTextExample {
    public static void main(String[] args) {
        JFrame frame = new JFrame("Bold Text Example");   

        frame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
        frame.setSize(300, 100);

        JPanel panel = new JPanel();
        JLabel label = new JLabel("This is a text lane with \"clarity\" in bold blue letters.");

        // Create a font with bold style and blue color
        Font font = new Font("Arial", Font.BOLD, 14);
        label.setFont(font);

        // Set the text color to blue
        label.setForeground(Color.BLUE);

        panel.add(label);
        frame.add(panel);

        frame.setVisible(true);
