https://drive.google.com/drive/folders/1cCQKv_N2sfqDn8hfCPsiZQqydSKDfdqW?usp=drive_link

(x_train, y_train), (x_test, y_test) = tf.keras.datasets.mnist.load_data()
x_test = x_test / 255.0
print(x_test.shape)
