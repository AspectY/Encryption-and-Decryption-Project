This program for a graphical user interface (GUI) allows the user to encrypt and decrypt files
using the DES encryption algorithm. The program uses Swing, which is a Java GUI toolkit, to
create the GUI components such as buttons, text fields, and labels.

The program creates a JFrame and sets its layout to a 5x2 grid. It then creates several JLabels
and JTextFields for the user to input the secret key, input file path, encrypted file path, and
decrypted file path. The program also creates two JButtons, "Encrypt" and "Decrypt", which
perform the corresponding actions when clicked.

The "Encrypt" button performs file encryption using the DESEncryption.encryptFile() method
and displays a success or error message in a JOptionPane dialogue box. The "Decrypt" button
performs file decryption using the DESEncryption.decryptFile() method and displays a success
or error message in a JOptionPane dialogue box.

Overall, this program provides a simple and user-friendly way to encrypt and decrypt files using
the DES algorithm.
