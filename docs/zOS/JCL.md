# Job Control Language (JCL)

Introduction to JCL...

## Job Cards
Job Cards provide information to the system (and those looking at the JCL) about the job that is being submitted. Information such as:

- :man_shrugging: Who owns the job
- :money_mouth_face: Who should be billed for the job*
- :leftwards_arrow_with_hook: What system should the job run on
- :page_facing_up: Where should the job output go (think STDOUT)
- and more...

**A Job Card must be the first statement in a job. Without it, the job will not be read.**

A Job Card typically looks like this:

```
//JOBNAME  JOB ([account info][,more account info]),'PROGRAMMER NAME',
//               MSGCLASS=A,CLASS=A,NOTIFY=&SYSUID
```
So, my job cards often look like this:

```
//OSCARCJ1  JOB ,'OSCAR C',MSGCLASS=A,CLASS=A,NOTIFY=&SYSUID
```
Notice that I've ommited any accounting information? This is barely used anymore, and so can happily be left out.
### Job Card Parameters


## Types of Statements

## How Production JCL looks

## Samples

### Sample 1: IEFBR14 Job

### Sample 2: IDCAMS Copy