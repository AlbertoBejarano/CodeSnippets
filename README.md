# CodeSnippets

install.packages("GGally", repos='http://cran.us.r-project.org')

df.columns.tolist()

conda install -c bioconda os

df = pd.read_csv('file.tar.gz', compression='gzip', header=0, sep='\t', quotechar='"', error_bad_lines=False)

pd.read_csv(file, low_memory=False,usecols=lambda c: not c.startswith('Unnamed:'))

usecols=lambda c: not c.startswith('Unnamed:')

df['Condition'] == "After food"

plt.scatter(outputs[:,0], outputs[:,1], s=1, c=y_train, cmap='rainbow')




#!pip uninstall umap
#!pip install umap-learn
import umap.umap_ as umap



!pip install umap-learn[plot]
!pip install holoviews
!pip install -U ipykernel
