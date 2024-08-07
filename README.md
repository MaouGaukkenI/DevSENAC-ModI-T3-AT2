# Hospital Management System

## Objective

This project aims to create a database for managing hospital information. The database structure includes tables to store data about patients, doctors, insurance companies, specializations, appointments, prescriptions, nurses, rooms, and hospital admissions.

## Database Structure

1. **Patients**: Stores personal information about patients, including name, date of birth, address, phone, email, CPF, and RG.

2. **Insurance**: Contains data about patient insurance, including name and CNPJ.

3. **Grace_Period**: Records the grace period for each patient regarding their insurance.

4. **Doctors**: Stores data about doctors, including name, date of birth, address, phone, and email.

5. **Specializations**: Lists the specializations available in the hospital.

6. **Doctor_Specialization**: Links doctors with their specializations.

7. **Appointments**: Records information about appointments, including date and time, doctor, patient, consultation fee, insurance, and specialty.

8. **Prescriptions**: Stores medical prescriptions, including medication, quantity, usage instructions, and the associated appointment.

9. **Nurses**: Contains data about nurses, such as name, CPF, and CRE.

10. **Nurse_Admission**: Links nurses to hospital admissions.

11. **Room_Types**: Defines the types of rooms available in the hospital.

12. **Rooms**: Records information about rooms, including number and type.

13. **Admissions**: Stores details about hospital admissions, such as entry and discharge dates, procedures performed, associated room, nurse, doctor, and patient.

14. **Room_Admission**: Links rooms with admissions.

## Usage

To start using the database, create the database with the SQL command `CREATE DATABASE`, select the database with `USE`, and then create the tables with the provided commands. The structure is designed to efficiently manage all hospital-related information.

# Sistema de Gerenciamento Hospitalar-Traduzido:

## Objetivo

Este projeto visa criar um banco de dados para gerenciar informações de um hospital. A estrutura do banco de dados inclui tabelas para armazenar dados sobre pacientes, médicos, convenios, especializações, consultas, receitas, enfermeiros, quartos e internações.

## Estrutura do Banco de Dados

1. **Pacientes**: Armazena informações pessoais dos pacientes, como nome, data de nascimento, endereço, telefone, e-mail, CPF e RG.

2. **Convenio**: Contém dados sobre os convênios dos pacientes, incluindo nome e CNPJ.

3. **Tempo_de_carencia**: Registra o tempo de carência de cada paciente em relação ao seu convênio.

4. **Medicos**: Armazena dados dos médicos, como nome, data de nascimento, endereço, telefone e e-mail.

5. **Especializacoes**: Lista as especializações disponíveis no hospital.

6. **Medico_especializacao**: Relaciona médicos com suas especializações.

7. **Consulta**: Registra informações sobre consultas realizadas, incluindo data e hora, médico, paciente, valor da consulta, convênio e especialidade.

8. **Receitas**: Armazena receitas médicas, incluindo medicamento, quantidade, instruções de uso e a consulta associada.

9. **Enfermeiros**: Contém dados dos enfermeiros, como nome, CPF e CRE.

10. **Enfermeiro_internacao**: Relaciona enfermeiros com internações.

11. **Tipo_de_quarto**: Define os tipos de quartos disponíveis no hospital.

12. **Quartos**: Registra informações sobre os quartos, incluindo número e tipo.

13. **Internacao**: Armazena detalhes sobre internações, como datas de entrada e alta, procedimentos realizados, quarto, enfermeiro, médico e paciente associados.

14. **Quarto_internacao**: Relaciona quartos com internações.

## Utilização

Para começar a utilizar o banco de dados, crie o banco com o comando SQL `CREATE DATABASE`, selecione o banco com `USE`, e então crie as tabelas com os comandos fornecidos. A estrutura está projetada para suportar a gestão eficiente de todas as informações hospitalares.
