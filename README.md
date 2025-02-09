# Bionic Arm with AI
This project is about the construction of a 3D bionic arm that receives biological signals from the arm of a person. With these signals, the movements of the 3D arm are controlled.

The next image to the left shows  the bionic arm printed in 3D and to the right the 3D model.

![arm3d](https://user-images.githubusercontent.com/19544865/71301620-24e51380-2380-11ea-8530-0efa341050da.png)

Additionally, the bionic arm has an Arduino Due in which runs a Support Vector Machine (SVM) to classify movements based on the features calculated over the EMG signal from the arm of a person. The implemented SVM can recognize 4 movements: cylindrical for holding a cylindrical tool, hook for supporting a heavy load, clenched fist and quiet hand. The next figure shows the 4 movements

![mov4_cut](https://user-images.githubusercontent.com/19544865/71301628-5067fe00-2380-11ea-9b75-e6c8c13cf8f6.png)






# Block diagram of the system
This image shows the block diagram of the complete system 

![bloquesFin](https://user-images.githubusercontent.com/19544865/71300837-74731180-2377-11ea-8052-e60912d621a5.png)
