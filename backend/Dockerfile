FROM plone/plone-backend:6.0.0a2

# Add local code
COPY . ./
RUN ./bin/pip install -r requirements.txt --use-deprecated legacy-resolver
