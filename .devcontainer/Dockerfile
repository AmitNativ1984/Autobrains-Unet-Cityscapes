ARG BASE_IMAGE
FROM $BASE_IMAGE as dev

RUN pip install ipywidgets --user widgetsnbextension
RUN jupyter nbextension enable --py widgetsnbextension

