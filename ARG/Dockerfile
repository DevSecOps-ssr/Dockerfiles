ARG version
FROM almalinux:${version:-8}
ARG employee_id = 20241209 \
    employee_name = "Sivaram" \
    designation = "DevOps Engineer" \
    company_name = "ProcessQ"
RUN echo "Working as a ${designation} at ${company_name}"
CMD [ "sleep", "200" ]