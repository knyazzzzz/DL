## Репозиторий для хранения и демонстрации DL (neural nets) пет-проектов 
*Deep learning (neural nets) python pet-projects, including the most important methods/attributes to work with neural nets, train them and predict results*
- [`pet_proj_DL_num_recognition`](https://github.com/knyazzzzz/pet-projects-DL/blob/main/pet_proj_DL_num_recognition.ipynb) 

Первый проект, показана работа с основными методами tensorflow + keras для организации работы нейронных сетей, выбор активационных функций нейронов, параметров их компиляции и сравнение эффективности нейронных сетей построением confusion matrix, а также методы визуализации входных данных с помощью matplotlib.pyplot, sklearn

*tensorflow+keras* 
>.datasets.mnist.load_data() 🦎 keras.Sequential() 🦎 keras.layers.Dense( ,input_shape= ,activation= ) 🦎  .compile(optimizer= , loss= , metrics= ) 🦎 .fit( ,epochs= ) 🦎 .evaluate() 🦎 .predict() 🦎 tf.math.confusion_matrix(labels= ,predictions= )

*seaborn, matplotlib.pyplot & numpy* 
>plt.matshow() 🦎 sns.heatmap(annot= , fmt= ) 🦎 np.reshape() 🦎 np.shape 🦎 np.argmax()

Подробное описание в самом блокноте проекта
