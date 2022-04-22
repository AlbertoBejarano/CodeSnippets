# CodeSnippets

install.packages("GGally", repos='http://cran.us.r-project.org')

df.columns.tolist()

conda install -c bioconda os

df = pd.read_csv('file.tar.gz', compression='gzip', header=0, sep='\t', quotechar='"', error_bad_lines=False)

pd.read_csv(file, low_memory=False,usecols=lambda c: not c.startswith('Unnamed:'))

usecols=lambda c: not c.startswith('Unnamed:')

df['Condition'] == "After food"

plt.scatter(outputs[:,0], outputs[:,1], s=1, c=y_train, cmap='rainbow')



plt.subplots(figsize=(25, 50))
count = 1
for i in range(len(num_data.columns)-1):
    plt.subplot(14, 4, count)
    sns.scatterplot(x=num_data.columns[i], y=num_data.columns[i+1],
                        data=num_data, color='red')
    count += 1
plt.show()



df.describe(include='object')


#!pip uninstall umap
#!pip install umap-learn
import umap.umap_ as umap

!pip install holoviews

!pip install umap-learn[plot]
!pip holoviews==1.12.7
!pip install -U ipykernel

!git clone https://github.com/lmcinnes/umap
!cd umap
!pip install --user -r requirements.txt
!python setup.py install --user

!pip install 'umap-learn==0.3.10'


