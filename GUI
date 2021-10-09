import java.awt.EventQueue;

import javax.swing.JFrame;
import javax.swing.JPanel;
import javax.swing.JComboBox;
import javax.swing.JLabel;
import javax.swing.JOptionPane;

import java.awt.Font;
import javax.swing.JTextField;
import javax.swing.JCheckBox;
import javax.swing.JButton;
import javax.swing.JRadioButton;
import java.awt.event.ActionListener;
import java.awt.event.ActionEvent;

public class GUI {

	private JFrame frame;
	private JTextField textField;
	private JTextField textField_1;
	private JTextField textField_2;
	private JTextField textField_3;

	
	public static void main(String[] args) {
		EventQueue.invokeLater(new Runnable() {
			public void run() {
				try {
					GUI window = new GUI();
					window.frame.setVisible(true);
				} catch (Exception e) {
					e.printStackTrace();
				}
			}
		});
	}

	
	public GUI() {
		initialize();
	}

	
	private void initialize() {
		frame = new JFrame();
		frame.setBounds(100, 100, 639, 746);
		frame.setDefaultCloseOperation(JFrame.EXIT_ON_CLOSE);
		frame.getContentPane().setLayout(null);
		
		//String[] dropdown = {"Select Item", "Signed Lebron James Jersey $499.99", "Dinosaur Fossil $999.99", "Game Worn Jordans $749.99", "Vintage Car $30000.00", "Elvis Presley Guitar $926.99"};
		
		JLabel lblNewLabel = new JLabel("*Limit one item per customer");
		lblNewLabel.setBounds(174, 77, 205, 16);
		frame.getContentPane().add(lblNewLabel);
		

		
		JLabel lblNewLabel_5 = new JLabel("Extremely Rare Collectables");
		lblNewLabel_5.setFont(new Font("Lucida Grande", Font.BOLD, 24));
		lblNewLabel_5.setBounds(121, 21, 366, 27);
		frame.getContentPane().add(lblNewLabel_5);
		
		JLabel lblNewLabel_6 = new JLabel("Shipping Information");
		lblNewLabel_6.setFont(new Font("Lucida Grande", Font.PLAIN, 16));
		lblNewLabel_6.setBounds(39, 231, 197, 32);
		frame.getContentPane().add(lblNewLabel_6);
		
		JLabel lblNewLabel_7 = new JLabel("Name:");
		lblNewLabel_7.setBounds(49, 263, 61, 16);
		frame.getContentPane().add(lblNewLabel_7);
		
		textField = new JTextField();
		textField.setBounds(96, 258, 283, 26);
		frame.getContentPane().add(textField);
		textField.setColumns(10);
		
		JLabel lblNewLabel_8 = new JLabel("Address:");
		lblNewLabel_8.setBounds(39, 291, 61, 16);
		frame.getContentPane().add(lblNewLabel_8);
		
		textField_1 = new JTextField();
		textField_1.setBounds(96, 286, 283, 26);
		frame.getContentPane().add(textField_1);
		textField_1.setColumns(10);
		
		JLabel lblNewLabel_9 = new JLabel("City:");
		lblNewLabel_9.setBounds(384, 291, 39, 16);
		frame.getContentPane().add(lblNewLabel_9);
		
		textField_2 = new JTextField();
		textField_2.setBounds(414, 286, 159, 26);
		frame.getContentPane().add(textField_2);
		textField_2.setColumns(10);
		
		JLabel lblNewLabel_10 = new JLabel("State:");
		lblNewLabel_10.setBounds(60, 319, 61, 16);
		frame.getContentPane().add(lblNewLabel_10);
		
		textField_3 = new JTextField();
		textField_3.setBounds(96, 314, 61, 26);
		frame.getContentPane().add(textField_3);
		textField_3.setColumns(10);
		
		JLabel lblNewLabel_11 = new JLabel("Delivery:");
		lblNewLabel_11.setFont(new Font("Lucida Grande", Font.PLAIN, 16));
		lblNewLabel_11.setBounds(39, 352, 107, 27);
		frame.getContentPane().add(lblNewLabel_11);
		
		JLabel ship = new JLabel("Shipping");
		ship.setBounds(49, 489, 223, 27);
		frame.getContentPane().add(ship);
		
		JCheckBox chckbxNewCheckBox = new JCheckBox("Fastest (1 day)");
		chckbxNewCheckBox.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {
				ship.setText("Fastest $49.99");
			}
		});
		chckbxNewCheckBox.setBounds(49, 382, 128, 23);
		frame.getContentPane().add(chckbxNewCheckBox);
		
		JCheckBox chckbxNewCheckBox_1 = new JCheckBox("Fast (3-5 days)");
		chckbxNewCheckBox_1.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {
				ship.setText("Fast $19.99");
			}
		});
		chckbxNewCheckBox_1.setBounds(236, 382, 128, 23);
		frame.getContentPane().add(chckbxNewCheckBox_1);
		
		JCheckBox chckbxNewCheckBox_2 = new JCheckBox("Standard (7 days)");
		chckbxNewCheckBox_2.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {
				ship.setText("Standard $6.99");
			}
		});
		chckbxNewCheckBox_2.setBounds(414, 382, 159, 23);
		frame.getContentPane().add(chckbxNewCheckBox_2);
		
		JLabel order = new JLabel("Order Unplaced");
		order.setFont(new Font("Lucida Grande", Font.PLAIN, 16));
		order.setBounds(236, 599, 215, 32);
		frame.getContentPane().add(order);

		
		JButton btnNewButton = new JButton("Confirm Order");
		btnNewButton.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {
				order.setText("Order Placed");
			}
		});
		btnNewButton.setFont(new Font("Lucida Grande", Font.PLAIN, 20));
		btnNewButton.setBounds(204, 547, 179, 52);
		frame.getContentPane().add(btnNewButton);
		
		JLabel cart = new JLabel("Item");
		cart.setBounds(49, 463, 315, 27);
		frame.getContentPane().add(cart);
		
		JRadioButton jersey = new JRadioButton("Signed Lebron Jersey $499.99");
		jersey.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {
				cart.setText("Signed Lebron Jersey $499.99");
			}
		});
		jersey.setBounds(49, 113, 245, 23);
		frame.getContentPane().add(jersey);
		
		JRadioButton fossil = new JRadioButton("Dinosaur Fossil $999.99");
		fossil.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {
				cart.setText("Dinosaur Fossil $999.99");
			}
		});
		fossil.setBounds(49, 148, 215, 23);
		frame.getContentPane().add(fossil);
		
		JRadioButton jordans = new JRadioButton("Game Worn Jordans $749.99");
		jordans.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {
				cart.setText("Game Worn Jordans $749.99");
			}
		});
		jordans.setBounds(49, 183, 215, 23);
		frame.getContentPane().add(jordans);
		
		JRadioButton car = new JRadioButton("Vintage Car $30000.00");
		car.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {
				cart.setText("Vintage Car $30000.00");
			}
		});
		car.setBounds(286, 129, 223, 23);
		frame.getContentPane().add(car);
		
		JRadioButton elvis = new JRadioButton("Elvis Presley Guitar $926.99");
		elvis.addActionListener(new ActionListener() {
			public void actionPerformed(ActionEvent e) {
				cart.setText("Elvis Presley Guitar $926.99");
			}
		});
		elvis.setBounds(286, 164, 223, 23);
		frame.getContentPane().add(elvis);
		
		JLabel lblNewLabel_4 = new JLabel();
		lblNewLabel_4.setBounds(39, 275, 61, 16);
		frame.getContentPane().add(lblNewLabel_4);
		
		JLabel lblNewLabel_1 = new JLabel("Cart:");
		lblNewLabel_1.setFont(new Font("Lucida Grande", Font.PLAIN, 16));
		lblNewLabel_1.setBounds(39, 439, 61, 16);
		frame.getContentPane().add(lblNewLabel_1);
			
		
		
	}
}
